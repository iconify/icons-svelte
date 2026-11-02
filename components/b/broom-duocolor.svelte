<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gilwoj1ah"/><path class="zcsz4bczm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:broom-duocolor" {...props}></Icon>
<style>
:global(.gilwoj1ah) {
  stroke-opacity: 0.4;
  d: path("M12 3v9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zcsz4bczm) {
  d: path("M12 20H4l4-8h8l4 8zm-2 0v-3m4 3v-3");
}

</style>
