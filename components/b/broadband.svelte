<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sn96usbwh"/><path class="tpryvsr9m"/><path class="x2nm_ob4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:broadband" {...props}></Icon>
<style>
:global(.sn96usbwh) {
  d: path("M12.205 19.5H6V10l7-6.5l7 6.5v2.395M2.5 14H6");
}

:global(.tpryvsr9m) {
  d: path("M15 18.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x2nm_ob4x) {
  d: path("M16.75 18.5a1.75 3.5 0 1 0 3.5 0a1.75 3.5 0 1 0-3.5 0Zm-1.75 0h7");
}

</style>
