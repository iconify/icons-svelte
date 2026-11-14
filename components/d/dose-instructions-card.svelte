<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq6975bfj"/><path class="m_wgazl2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dose-instructions-card" {...props}></Icon>
<style>
:global(.m_wgazl2o) {
  d: path("m19.5 14.5l2 2l-2 2");
}

:global(.rq6975bfj) {
  d: path("M12.2 21H3V2.5h14v10.6M3 7h14M6.5 11h7m-7 4h4m4.5 6.5V20a3.5 3.5 0 0 1 3.5-3.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
