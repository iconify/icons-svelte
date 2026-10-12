<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a-ga0lihp"/><path class="f8wpp6b9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bedtime-sharp" {...props}></Icon>
<style>
:global(.a-ga0lihp) {
  d: path("M12 3a6.5 6.5 0 0 0 9 9a9 9 0 1 1-9-9Z");
}

:global(.f8wpp6b9a) {
  d: path("M15.5 4.5H19l-3.5 4H19");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
