<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdz99q_zk"/><path class="agyq-23fr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mini-player" {...props}></Icon>
<style>
:global(.agyq-23fr) {
  d: path("m15 13.5l6.5 4.25L15 22Z");
}

:global(.jdz99q_zk) {
  d: path("M12.2 16H2.5V3h19v11.4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
