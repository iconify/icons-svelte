<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w4v1bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:ad-location" {...props}></Icon>
<style>
:global(.w0w4v1bve) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.106 3.983Q14.984 1.75 12 1.75T6.894 3.983Q4.75 6.24 4.75 9.5q0 6.328 6.741 12.551q.052.048.111.085t.125.063t.134.038t.139.013t.139-.013t.134-.038q.065-.026.125-.063q.059-.037.111-.085Q19.25 15.828 19.25 9.5q0-3.26-2.144-5.517");
}

</style>
