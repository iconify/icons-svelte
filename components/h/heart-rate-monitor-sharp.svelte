<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s77rrwb7q"/><path class="v4_0yckvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heart-rate-monitor-sharp" {...props}></Icon>
<style>
:global(.s77rrwb7q) {
  d: path("M2.75 3.75h18.5v13H2.75z");
}

:global(.v4_0yckvh) {
  d: path("M5.75 10.5h3L10 8l2 5.5l1.75-4l1 1h3.5M12 16.75v4.5m-3.75 0h7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
