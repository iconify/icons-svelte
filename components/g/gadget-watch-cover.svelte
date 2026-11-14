<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uem51cbps"/><path class="pb4-_3bdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gadget-watch-cover" {...props}></Icon>
<style>
:global(.pb4-_3bdw) {
  d: path("M12 9.5V12l1.5 1");
}

:global(.uem51cbps) {
  d: path("M8 6.5h8a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Zm1 0l.75-4h4.5l.75 4m-6 11l.75 4h4.5l.75-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
