<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rera8xt7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:card-travel-sharp" {...props}></Icon>
<style>
:global(.rera8xt7n) {
  fill: currentColor;
  d: path("M2 21V6h5V2h10v4h5v15zM9 6h6V4H9zM4 17h16v-3H4z");
}

</style>
