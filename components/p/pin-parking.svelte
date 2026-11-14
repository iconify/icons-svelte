<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es64dmb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:pin-parking" {...props}></Icon>
<style>
:global(.es64dmb4t) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.875 2.25h-5.75q-2.848 0-4.861 2.014T2.25 9.125v5.75q0 2.848 2.014 4.861t4.861 2.014h5.75q2.848 0 4.861-2.014t2.014-4.861v-5.75q0-2.848-2.014-4.861T14.875 2.25");
}

</style>
