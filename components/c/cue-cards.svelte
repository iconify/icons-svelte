<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pmae9eqmt"/><path class="ovssapbam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cue-cards" {...props}></Icon>
<style>
:global(.ovssapbam) {
  d: path("M6.5 7.5v-1a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2h-2M6 11h8m-8 3h8m-8 3h5");
}

:global(.pmae9eqmt) {
  d: path("M2.5 7.5h15V20h-15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
