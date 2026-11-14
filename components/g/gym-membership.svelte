<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4f4syb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:gym-membership" {...props}></Icon>
<style>
:global(.f4f4syb1u) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5.25q2.75 0 2.75 2.75v3.25h8.5V8q0-2.75 2.75-2.75T21.75 8v8q0 2.75-2.75 2.75T16.25 16v-3.25h-8.5V16q0 2.75-2.75 2.75T2.25 16V8q0-2.75 2.75-2.75");
}

</style>
