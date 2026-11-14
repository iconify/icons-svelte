<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2t1w64w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:confusion-matrix" {...props}></Icon>
<style>
:global(.xi2t1w64w) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 3.25h-1.25q-3.375 0-3.375 3.375v1.25q0 3.375 3.375 3.375h1.25q3.375 0 3.375-3.375v-1.25q0-3.375-3.375-3.375m8.25 0h1.25q3.375 0 3.375 3.375v1.25q0 3.375-3.375 3.375h-1.25q-3.375 0-3.375-3.375v-1.25q0-3.375 3.375-3.375m-8.25 9.5h-1.25q-3.375 0-3.375 3.375v1.25q0 3.375 3.375 3.375h1.25q3.375 0 3.375-3.375v-1.25q0-3.375-3.375-3.375m8.25 0h1.25q3.375 0 3.375 3.375v1.25q0 3.375-3.375 3.375h-1.25q-3.375 0-3.375-3.375v-1.25q0-3.375 3.375-3.375");
}

</style>
