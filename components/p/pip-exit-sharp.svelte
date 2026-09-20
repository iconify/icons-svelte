<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fumev6hpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pip-exit-sharp" {...props}></Icon>
<style>
:global(.fumev6hpg) {
  fill: currentColor;
  d: path("M2 20v-9h9V4h11v16zm15.075-3.5l1.425-1.425L15.4 12H18v-2h-6v6h2v-2.575zM2 9V4h7v5z");
}

</style>
