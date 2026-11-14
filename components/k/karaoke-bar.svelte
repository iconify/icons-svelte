<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5bcdvbpf"/><path class="nbbzyq9ti"/><path class="sbh-nd56v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:karaoke-bar" {...props}></Icon>
<style>
:global(.nbbzyq9ti) {
  d: path("M10.5 8h3v5h-3Z");
}

:global(.sbh-nd56v) {
  d: path("M7.75 11.5a4.25 4.25 0 0 0 8.5 0M12 15.75v2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v5bcdvbpf) {
  d: path("M3.5 10L12 3l8.5 7v11h-17Z");
}

</style>
