<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l37gi8omx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:degree-symbol" {...props}></Icon>
<style>
:global(.l37gi8omx) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 8.5q0-2.175 1.538-3.712Q9.825 3.25 12 3.25t3.712 1.538Q17.25 6.325 17.25 8.5t-1.538 3.712Q14.175 13.75 12 13.75t-3.712-1.538Q6.75 10.675 6.75 8.5");
}

</style>
