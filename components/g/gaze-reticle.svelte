<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9qxwohhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gaze-reticle" {...props}></Icon>
<style>
:global(.v9qxwohhc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 5.5v3m0 7v3M5.5 12h3m7 0h3M12 12h.01");
}

</style>
