<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypu1d9r4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-horizontal-rule" {...props}></Icon>
<style>
:global(.ypu1d9r4o) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 13H5c-.55 0-1-.45-1-1s.45-1 1-1h14c.55 0 1 .45 1 1s-.45 1-1 1");
}

</style>
