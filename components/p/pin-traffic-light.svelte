<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yta2dwbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:pin-traffic-light" {...props}></Icon>
<style>
:global(.yta2dwbao) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.712 3.288Q14.175 1.75 12 1.75T8.288 3.288Q6.75 4.825 6.75 7v10q0 2.175 1.538 3.712Q9.825 22.25 12 22.25t3.712-1.538Q17.25 19.175 17.25 17V7q0-2.175-1.538-3.712M10 6.5q0-2 2-2t2 2t-2 2t-2-2m2 3.5q2 0 2 2t-2 2t-2-2t2-2m-2 7.5q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
