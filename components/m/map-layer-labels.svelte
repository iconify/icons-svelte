<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ezo83iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:map-layer-labels" {...props}></Icon>
<style>
:global(.u_ezo83iq) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.375 2.25h-4.788q-1.398 0-2.386.989l-6.875 6.875q-2.386 2.386 0 4.772l4.788 4.788q2.386 2.386 4.772 0l6.875-6.875q.989-.988.989-2.386V5.625q0-1.398-.989-2.386q-.988-.989-2.386-.989M14.25 7.5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25");
}

</style>
