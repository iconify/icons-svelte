<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uubbe3tek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:bowling-ball" {...props}></Icon>
<style>
:global(.uubbe3tek) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8 7.25q0-2 2-2t2 2t-2 2t-2-2m7.5-1.5q2 0 2 2t-2 2t-2-2t2-2m-3 7.75q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
