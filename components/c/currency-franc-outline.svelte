<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="illmc7b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:currency-franc-outline" {...props}></Icon>
<style>
:global(.illmc7b9d) {
  fill: currentColor;
  d: path("M7 21v-3H5v-2h2V3h11v2H9v6h8v2H9v3h4v2H9v3z");
}

</style>
