<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfm7oobmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:infinity-loop-science" {...props}></Icon>
<style>
:global(.nfm7oobmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-3-6.5-9.5-6.5-9.5 0S9 18.5 12 12m0 0c3-6.5 9.5-6.5 9.5 0S15 18.5 12 12");
}

</style>
