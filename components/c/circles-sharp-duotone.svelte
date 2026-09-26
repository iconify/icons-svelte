<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xcygzbb7m"/><path class="ta-zbubhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circles-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ta-zbubhx) {
  d: path("M23 15C23 19.2803 19.2803 23 15 23C10.7197 23 7 19.2803 7 15C7 10.7197 10.7197 7 15 7C19.2803 7 23 10.7197 23 15Z");
}

:global(.xcygzbb7m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9C17 13.2803 13.2803 17 9 17C4.7197 17 1 13.2803 1 9C1 4.7197 4.7197 1 9 1C13.2803 1 17 4.7197 17 9Z");
}

</style>
