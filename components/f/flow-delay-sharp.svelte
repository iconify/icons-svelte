<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8gmi_brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flow-delay-sharp" {...props}></Icon>
<style>
:global(.a8gmi_brj) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 5L15 5C18.866 5 22 8.134 22 12C22 15.866 18.866 19 15 19L2 19Z");
}

</style>
