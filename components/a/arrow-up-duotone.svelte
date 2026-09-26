<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cctdabcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-duotone" {...props}></Icon>
<style>
:global(.cctdabcnh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11.8771L11.5875 5.17385C11.8153 4.94205 12.1847 4.94205 12.4125 5.17385L19 11.8771M12 19V5.94129");
}

</style>
