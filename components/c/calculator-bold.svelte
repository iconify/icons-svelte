<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wzkvo4h4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:calculator-bold" {...props}></Icon>
<style>
:global(.wzkvo4h4v) {
  fill: currentColor;
  d: path("M200 20H56a20 20 0 0 0-20 20v176a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V40a20 20 0 0 0-20-20m-4 192H60V44h136ZM80 76a12 12 0 0 1 12-12h72a12 12 0 0 1 0 24H92a12 12 0 0 1-12-12m40 52a16 16 0 1 1-16-16a16 16 0 0 1 16 16m48 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16m-48 48a16 16 0 1 1-16-16a16 16 0 0 1 16 16m48 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
