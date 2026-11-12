<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ufv0brdex"/><path class="g7lwt0b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:distort-broken" {...props}></Icon>
<style>
:global(.g7lwt0b0n) {
  d: path("M12 12C12 12 6 16 12 22M12 12C12 12 17 17 22 12M12 12C12 12 17 7 12 2M12 12C12 12 8 6 2 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ufv0brdex) {
  d: path("M7 3.3378C8.4709 2.487 10.1786 2 12 2C17.5228 2 22 6.4772 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 10.1786 2.487 8.4709 3.3378 7");
}

</style>
