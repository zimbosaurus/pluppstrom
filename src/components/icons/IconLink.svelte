<script lang="ts">
  export let href: string;
</script>

<a {href} target="_blank" class="cursor-pointer">
  <slot />
</a>
