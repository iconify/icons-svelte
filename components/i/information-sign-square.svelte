<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhua0ry8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:information-sign-square" {...props}></Icon>
<style>
:global(.xhua0ry8q) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 2.25h7.5q2.485 0 4.243 1.757Q21.75 5.765 21.75 8.25v7.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 18.235 2.25 15.75v-7.5q0-2.485 1.757-4.243Q5.765 2.25 8.25 2.25");
}

</style>
