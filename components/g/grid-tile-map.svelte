<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4jov36kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:grid-tile-map" {...props}></Icon>
<style>
:global(.i4jov36kp) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.75h-1.75q-3.375 0-3.375 3.375v1.75q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375m8.25 0h1.75q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375m-8.25 10h-1.75q-3.375 0-3.375 3.375v1.75q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375m8.25 0h1.75q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375");
}

</style>
