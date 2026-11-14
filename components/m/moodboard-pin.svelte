<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="turd34bgo"/><path class="fw2jq4b8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:moodboard-pin" {...props}></Icon>
<style>
:global(.fw2jq4b8n) {
  d: path("m7.5 17.5l3-4L13 16l1.5-1.5l2 3");
}

:global(.turd34bgo) {
  d: path("M4.5 7h15v13.5h-15Zm5.25-2.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM12 6.75V9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
