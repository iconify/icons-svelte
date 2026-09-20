<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wcqw0plzt"/><path class="c5k958sty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-left-duotone" {...props}></Icon>
<style>
:global(.c5k958sty) {
  d: path("M237.66 90.34a8 8 0 0 0-11.32 0L136 180.69L71.31 116l30.35-30.34A8 8 0 0 0 96 72H24a8 8 0 0 0-8 8v72a8 8 0 0 0 13.66 5.66L60 127.31l70.34 70.35a8 8 0 0 0 11.32 0l96-96a8 8 0 0 0 0-11.32M32 132.69V88h44.69Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.wcqw0plzt) {
  d: path("m96 80l-72 72V80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
