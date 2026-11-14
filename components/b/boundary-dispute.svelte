<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r525pqx_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boundary-dispute" {...props}></Icon>
<style>
:global(.r525pqx_n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h2.5V20H3Zm6 0h2.5V20H9Zm6 0h2.5V20H15ZM5.5 9H9m-3.5 6.5H9M11.5 9H15m-3.5 6.5H15m5.5-1V18m0 3h.01");
}

</style>
