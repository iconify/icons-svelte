<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e36ii353l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:burst-mode" {...props}></Icon>
<style>
:global(.e36ii353l) {
  fill: currentColor;
  d: path("M1.77 18V6h1v12zM6 18V6h1v12zm5.846 0q-.69 0-1.153-.462t-.462-1.153v-8.77q0-.69.462-1.152T11.846 6h8.77q.69 0 1.152.463t.463 1.153v8.769q0 .69-.463 1.153T20.616 18zm.846-3.23h7.077l-2.138-2.886l-1.9 2.5l-1.4-1.85z");
}

</style>
