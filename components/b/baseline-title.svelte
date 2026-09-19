<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbie6beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-title" {...props}></Icon>
<style>
:global(.uqbie6beg) {
  fill: currentColor;
  d: path("M5 4v3h5.5v12h3V7H19V4z");
}

</style>
