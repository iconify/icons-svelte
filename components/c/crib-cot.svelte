<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha14fk7gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crib-cot" {...props}></Icon>
<style>
:global(.ha14fk7gk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4v16.5M20 4v16.5M4 7h16M4 16h16M8 7v9m4-9v9m4-9v9");
}

</style>
