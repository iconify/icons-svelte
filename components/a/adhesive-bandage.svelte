<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e317htbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:adhesive-bandage" {...props}></Icon>
<style>
:global(.e317htbga) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.581 10.409l-2.829 2.829q-1.245 1.244-1.245 3.005t1.245 3.005t3.005 1.245t3.005-1.245l2.829-2.829l5.657-5.657q1.245-1.244 1.245-3.005t-1.245-3.005q-1.244-1.245-3.005-1.245t-3.005 1.245z");
}

</style>
