<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gw-nor27e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naver-blog" {...props}></Icon>
<style>
:global(.gw-nor27e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.075 26.366c0-4.144 3.553-7.505 7.935-7.505s7.935 3.36 7.935 7.505v4.88c0 4.144-3.553 7.504-7.935 7.504s-7.935-3.36-7.935-7.505m0 7.506V8.73M36.925 5v38");
}

</style>
