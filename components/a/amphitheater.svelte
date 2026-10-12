<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxnpnbbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:amphitheater" {...props}></Icon>
<style>
:global(.fxnpnbbag) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5a9.25 9.25 0 0 0 18.5 0m-15.5 0a6.25 6.25 0 0 0 12.5 0m-9.5 0a3.25 3.25 0 0 0 6.5 0M5.5 18.75h13");
}

</style>
