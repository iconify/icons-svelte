<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpm9637lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:hexagon" {...props}></Icon>
<style>
:global(.gpm9637lk) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.688 2.358l5.818 3.359q1.688.975 1.688 2.924v6.718q0 1.949-1.688 2.924l-5.818 3.359q-1.687.974-3.375 0l-5.819-3.359q-1.688-.975-1.688-2.924V8.641q0-1.949 1.688-2.924l5.819-3.359q1.688-.974 3.375 0");
}

</style>
