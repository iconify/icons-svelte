<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcyt748_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:component-description" {...props}></Icon>
<style>
:global(.pcyt748_v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.856 4.606l1.788 1.788a2.625 2.625 0 0 1 0 3.712l-1.788 1.788a2.625 2.625 0 0 1-3.712 0l-1.788-1.788a2.625 2.625 0 0 1 0-3.712l1.788-1.788a2.625 2.625 0 0 1 3.712 0M4 17.25h16M4 21h10");
}

</style>
