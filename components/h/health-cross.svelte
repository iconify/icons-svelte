<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0jl5lbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:health-cross" {...props}></Icon>
<style>
:global(.l0jl5lbej) {
  fill: currentColor;
  d: path("M8 21v-5H3V8h5V3h8v5h5v8h-5v5z");
}

</style>
