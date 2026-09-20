<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6rg0hmbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bed-outline-sharp" {...props}></Icon>
<style>
:global(.i6rg0hmbr) {
  fill: currentColor;
  d: path("M3 18v-7h1V7h16v4h1v7h-1v-2H4v2zm9.5-7H19V8h-6.5zM5 11h6.5V8H5zm-1 4h16v-3H4zm16 0H4z");
}

</style>
