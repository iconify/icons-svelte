<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a-ga0lihp"/><path class="uj6dw-a6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:moon-fog-sharp" {...props}></Icon>
<style>
:global(.a-ga0lihp) {
  d: path("M12 3a6.5 6.5 0 0 0 9 9a9 9 0 1 1-9-9Z");
}

:global(.uj6dw-a6t) {
  d: path("m17.5 3.75l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42l-2.42-.33l2.42-.33z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
