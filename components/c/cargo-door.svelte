<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xjarste7a"/><path class="lf1r0bc6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cargo-door" {...props}></Icon>
<style>
:global(.lf1r0bc6l) {
  d: path("M5.5 10.5h6v7h-6Zm0 2.75h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xjarste7a) {
  d: path("M14.5 3.5h-10a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2h10Zm0 0l7 3v11l-7 3");
}

</style>
