<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgfwhzar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:referee-whistle" {...props}></Icon>
<style>
:global(.sfgfwhzar) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 5.75H9.003q-2.762-.02-4.636 2.009q-1.875 2.031-1.635 4.784t2.439 4.428q2.198 1.675 4.916 1.176t4.178-2.846q1.195-1.921.907-4.051H20q2.25 0 2.25-2.25V8q0-2.25-2.25-2.25M6.25 12q0-2.75 2.75-2.75T11.75 12T9 14.75T6.25 12");
}

</style>
