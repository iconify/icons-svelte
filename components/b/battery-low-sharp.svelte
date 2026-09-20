<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcm4_ib0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-low-sharp" {...props}></Icon>
<style>
:global(.xcm4_ib0f) {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h11V9H6z");
}

</style>
