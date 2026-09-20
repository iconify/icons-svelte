<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgpk1cbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:full-coverage" {...props}></Icon>
<style>
:global(.rgpk1cbyf) {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V8h1v10.385q0 .23.192.423t.423.192H18v1zm4-4q-.691 0-1.153-.462T7 14.385V4h15v10.385q0 .69-.462 1.153T20.385 16zM10 12h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4z");
}

</style>
