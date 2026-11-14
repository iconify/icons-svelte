<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_yfgibqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:component-variant" {...props}></Icon>
<style>
:global(.q_yfgibqq) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.591 3.031q-.659-.66-1.591-.66t-1.591.66l-7.378 7.378q-.66.659-.66 1.591t.66 1.591l7.378 7.378q.659.66 1.591.66t1.591-.66l7.378-7.378q.66-.659.66-1.591t-.66-1.591zm0 6l1.378 1.378q.66.659.66 1.591t-.66 1.591l-1.378 1.378q-.659.66-1.591.66t-1.591-.66l-1.378-1.378q-.66-.659-.66-1.591t.66-1.591l1.378-1.378q.659-.66 1.591-.66t1.591.66");
}

</style>
