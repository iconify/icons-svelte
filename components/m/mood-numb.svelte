<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqcxwgr2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:mood-numb" {...props}></Icon>
<style>
:global(.nqcxwgr2a) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m7-4.75q-2.5 0-2.5 3.25t2.5 3.25t2.5-3.25t-2.5-3.25m4 3.25q0 3.25 2.5 3.25t2.5-3.25t-2.5-3.25t-2.5 3.25");
}

</style>
