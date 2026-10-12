<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdk7g22cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:non-binary-symbol" {...props}></Icon>
<style>
:global(.vdk7g22cu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.25a5.5 5.5 0 1 1 0 11a5.5 5.5 0 1 1 0-11m0 0v-7.5m-2.5 1.5l5 3m0-3l-5 3");
}

</style>
