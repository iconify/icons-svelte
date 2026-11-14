<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rswdo2b9h"/><path class="arxa1nb2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-new-in" {...props}></Icon>
<style>
:global(.arxa1nb2x) {
  fill: currentColor;
  d: path("M12 6.25q.5 5.25 4 5.75q-3.5.5-4 5.75q-.5-5.25-4-5.75q3.5-.5 4-5.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rswdo2b9h) {
  d: path("m13.034 2.983l.509.485a1.5 1.5 0 0 0 1.386.372l.684-.166a1.5 1.5 0 0 1 1.791 1.034l.199.675a1.5 1.5 0 0 0 1.014 1.014l.675.199a1.5 1.5 0 0 1 1.034 1.791l-.166.684a1.5 1.5 0 0 0 .372 1.386l.485.509a1.5 1.5 0 0 1 0 2.068l-.485.509a1.5 1.5 0 0 0-.372 1.386l.166.684a1.5 1.5 0 0 1-1.034 1.791l-.675.199a1.5 1.5 0 0 0-1.014 1.014l-.199.675a1.5 1.5 0 0 1-1.791 1.034l-.684-.166a1.5 1.5 0 0 0-1.386.372l-.509.485a1.5 1.5 0 0 1-2.068 0l-.509-.485a1.5 1.5 0 0 0-1.386-.372l-.684.166a1.5 1.5 0 0 1-1.791-1.034l-.199-.675a1.5 1.5 0 0 0-1.014-1.014l-.675-.199a1.5 1.5 0 0 1-1.034-1.791l.166-.684a1.5 1.5 0 0 0-.372-1.386l-.485-.509a1.5 1.5 0 0 1 0-2.068l.485-.509a1.5 1.5 0 0 0 .372-1.386l-.166-.684a1.5 1.5 0 0 1 1.034-1.791l.675-.199a1.5 1.5 0 0 0 1.014-1.014l.199-.675a1.5 1.5 0 0 1 1.791-1.034l.684.166a1.5 1.5 0 0 0 1.386-.372l.509-.485a1.5 1.5 0 0 1 2.068 0");
}

</style>
