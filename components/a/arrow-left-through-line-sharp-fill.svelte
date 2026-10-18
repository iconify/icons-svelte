<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn_u56bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-through-line-sharp-fill" {...props}></Icon>
<style>
:global(.fn_u56bsn) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12L3 12M7.2929 16.2929L3 12L7.2929 7.7071M12 2L12 9M12 15L12 22");
}

</style>
