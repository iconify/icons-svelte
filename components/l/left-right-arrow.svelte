<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u1eahdbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:left-right-arrow" {...props}></Icon>
<style>
:global(.u1eahdbgm) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M44.3 51.91V31.85L.46 63.99L44.3 96.15V76.1h39.4v20.05L127.54 64L83.7 31.85v20.06z");
}

</style>
