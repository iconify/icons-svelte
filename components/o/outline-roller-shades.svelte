<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkuzi3b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-roller-shades" {...props}></Icon>
<style>
:global(.fkuzi3b9r) {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM18 5v6H6V5zM6 19v-6h5v1.82A1.746 1.746 0 0 0 12 18a1.746 1.746 0 0 0 1-3.18V13h5v6z");
}

</style>
