<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkn4s7hnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:banker-lamp-sharp" {...props}></Icon>
<style>
:global(.lkn4s7hnf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 10.5l1-4l.25-1h10.5l.25 1l1 4Zm6.5 0v7.75m4-7.75v2.75m-9.5 5h11v3h-11z");
}

</style>
