<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cucmds3jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:log-out-sharp-fill" {...props}></Icon>
<style>
:global(.cucmds3jf) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 4L3 4L3 20L10 20M20.7586 12L9.1093 12M14.8562 6.204L21 12L14.8562 17.796");
}

</style>
