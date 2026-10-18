<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":296};
const content = `<g class="zl_6kdbye"><path class="el28nubaq"/><path class="pqz4-3bcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:luma-icon" {...props}></Icon>
<style>
:global(.el28nubaq) {
  d: path("m0 221.965l128 73.989V0L0 73.988z");
}

:global(.pqz4-3bcn) {
  d: path("m128 295.954l128-73.989l-128-73.988L0 221.965z");
}

:global(.zl_6kdbye) {
  fill-opacity: var(--svg-fill-opacity--0-65, 0.65);
}

</style>
