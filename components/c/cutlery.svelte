<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-pjypbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cutlery" {...props}></Icon>
<style>
:global(.n-pjypbry) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.75v4a2.5 2.5 0 0 0 5 0v-4m-2.5 0v18.5m8.5-1.75v-5.25h-.75V7.5c0-2.6 1.35-4.75 3.25-4.75h.25V19.5a1.38 1.38 0 0 1-2.75 0");
}

</style>
