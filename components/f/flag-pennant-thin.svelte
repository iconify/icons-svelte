<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fbshizb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:flag-pennant-thin" {...props}></Icon>
<style>
:global(.fbshizb6u) {
  fill: currentColor;
  d: path("m241.31 100.22l-184-64A4 4 0 0 0 52 40v176a4 4 0 0 0 8 0v-45.16l181.31-63.06a4 4 0 0 0 0-7.56M60 162.37V45.63L227.82 104Z");
}

</style>
