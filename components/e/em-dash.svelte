<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2_q0pb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:em-dash" {...props}></Icon>
<style>
:global(.i2_q0pb4e) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 9.75h16q2.25 0 2.25 2.25T20 14.25H4q-2.25 0-2.25-2.25T4 9.75");
}

</style>
