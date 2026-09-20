<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c1u3z-bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:link-simple-bold" {...props}></Icon>
<style>
:global(.c1u3z-bue) {
  fill: currentColor;
  d: path("m87.5 151.52l64-64a12 12 0 0 1 17 17l-64 64a12 12 0 0 1-17-17m131-114a60.08 60.08 0 0 0-84.87 0l-30.12 30.09a12 12 0 0 0 17 17l30.07-30.06a36 36 0 0 1 50.93 50.92l-30.11 30.05a12 12 0 1 0 17 17l30.08-30.06a60.09 60.09 0 0 0-.03-84.91ZM135.52 171.4l-30.07 30.08a36 36 0 0 1-50.92-50.93l30.06-30.07a12 12 0 0 0-17-17l-30.04 30.1a60 60 0 0 0 84.88 84.87l30.06-30.07a12 12 0 0 0-17-17Z");
}

</style>
