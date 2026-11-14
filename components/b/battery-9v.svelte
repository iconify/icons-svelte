<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y3u9b-bpw"/><path class="adhyun7ou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-9v" {...props}></Icon>
<style>
:global(.adhyun7ou) {
  d: path("m9.5 10.5l2.5 5l2.5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y3u9b-bpw) {
  d: path("M6.5 6h11v15.5h-11Zm2.75-2.75V6m5.5-2.75V6");
}

</style>
