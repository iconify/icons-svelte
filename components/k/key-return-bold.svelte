<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f3ntkdrmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:key-return-bold" {...props}></Icon>
<style>
:global(.f3ntkdrmi) {
  fill: currentColor;
  d: path("M71.51 144.49a12 12 0 0 1 0-17l24-24a12 12 0 0 1 17 17L109 124h55v-20a12 12 0 0 1 24 0v32a12 12 0 0 1-12 12h-67l3.52 3.51a12 12 0 0 1-17 17ZM236 56v144a20 20 0 0 1-20 20H40a20 20 0 0 1-20-20V56a20 20 0 0 1 20-20h176a20 20 0 0 1 20 20m-24 4H44v136h168Z");
}

</style>
