<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="srrgwbc_i"/><path class="k2j_68bqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camp-blanket" {...props}></Icon>
<style>
:global(.k2j_68bqp) {
  d: path("M17.5 5v3.5H21M14 5v6m0 2.75v6");
}

:global(.srrgwbc_i) {
  d: path("M5.5 5h12L21 8.5V11H5.5a3 3 0 0 1 0-6Zm0 8.75H21v6H5.5a3 3 0 0 1 0-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
