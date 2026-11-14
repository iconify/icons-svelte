<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cvnc7cb1k"/><path class="jnof8gp5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:live-mic-mute" {...props}></Icon>
<style>
:global(.cvnc7cb1k) {
  d: path("M7 3h4a1 1 0 0 1 1 1v8.5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

:global(.jnof8gp5m) {
  d: path("M3 10.5a6 6 0 0 0 12 0m-6 6V21m7.5-17l4 4m0-4l-4 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
