<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo_u_b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:glass-cup" {...props}></Icon>
<style>
:global(.yxo_u_b3g) {
  fill: currentColor;
  d: path("M7.475 21q-.621 0-1.087-.404q-.467-.404-.522-1.025L4 3h16l-1.846 16.571q-.056.621-.522 1.025T16.544 21zm-.938-4.5h10.952L18.866 4H5.116z");
}

</style>
