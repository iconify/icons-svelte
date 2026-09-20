<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x7fjqrbee"/><path class="jmqgxtb3w"/><path class="eugjv3bjh"/><path class="a8a2av-of"/><path class="gmnme03xt"/><path class="fl6wkhz5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:elm-classic" {...props}></Icon>
<style>
:global(.a8a2av-of) {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M256 113.806V0H142.193z");
}

:global(.eugjv3bjh) {
  fill: var(--svg-color--596277, #596277);
  d: path("M120.978 128L0 7.022V248.98z");
}

:global(.fl6wkhz5d) {
  fill: var(--svg-color--eea400, #eea400);
  d: path("m128 120.979l55.322-55.323H72.677z");
}

:global(.gmnme03xt) {
  fill: var(--svg-color--8cd636, #8cd636);
  d: path("m195.584 67.434l60.288 60.289l-60.563 60.564l-60.289-60.289zM7.021 0l55.725 55.726h121.129L128.15 0z");
}

:global(.jmqgxtb3w) {
  fill: var(--svg-color--eea400, #eea400);
  d: path("M202.332 195.311L256 248.98V141.643z");
}

:global(.x7fjqrbee) {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M128 135.022L7.023 256h241.955z");
}

</style>
