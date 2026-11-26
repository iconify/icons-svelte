<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0iui48jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:letter-spacing-sharp-fill" {...props}></Icon>
<style>
:global(.n0iui48jv) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.928 18.6273L12 6L17.072 18.6273M9.188 13L14.812 13M2 3L2 21M22 3L22 21");
}

</style>
