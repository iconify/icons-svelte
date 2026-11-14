<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tslyur56h"/><path class="edkl8j64e"/><path class="e-36feb-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-note-attach" {...props}></Icon>
<style>
:global(.e-36feb-c) {
  d: path("M18.5 22v-3.25h3.25");
}

:global(.edkl8j64e) {
  d: path("M14.25 14.5h7.5v4.25L18.5 22h-4.25Z");
}

:global(.tslyur56h) {
  d: path("M11.446 20.684L8.5 19L5 21V3h14v8.7M8.5 7.5h7m-7 3.5h7m-7 3.5h2.9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
