<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xcygzbb7m"/><path class="lvgl99b6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-square-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lvgl99b6v) {
  d: path("M9 8L22 8C22.5523 8 23 8.4477 23 9L23 22C23 22.5523 22.5523 23 22 23L9 23C8.4477 23 8 22.5523 8 22L8 9C8 8.4477 8.4477 8 9 8Z");
}

:global(.xcygzbb7m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9C17 13.2803 13.2803 17 9 17C4.7197 17 1 13.2803 1 9C1 4.7197 4.7197 1 9 1C13.2803 1 17 4.7197 17 9Z");
}

</style>
