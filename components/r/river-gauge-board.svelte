<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-hdbzw0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:river-gauge-board" {...props}></Icon>
<style>
:global(.d-hdbzw0u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15V2.5h6v10.6m0 5.9v2.5H9v-.6M9 5h3M9 9h3m-3 4h3M2 17q2.5-2 5 0t5 0t5 0t5 0");
}

</style>
