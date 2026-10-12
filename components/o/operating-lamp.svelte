<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qo6jfybal"/><path class="r62lgobwa"/><path class="k-bansbzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:operating-lamp" {...props}></Icon>
<style>
:global(.k-bansbzl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 17.25L6.75 21M12 17.25V21m4-3.75L17.25 21");
}

:global(.qo6jfybal) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v4.5M3.25 14a8.75 6.75 0 0 1 17.5 0Z");
}

:global(.r62lgobwa) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 11.25h.01m3.74-1h.01m3.74 1h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
