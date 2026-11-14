<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q61z0ib_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:comment-plus" {...props}></Icon>
<style>
:global(.q61z0ib_e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5M12 9v6m-3-3h6");
}

</style>
