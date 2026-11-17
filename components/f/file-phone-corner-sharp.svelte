<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oofbbnecl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-phone-corner-sharp" {...props}></Icon>
<style>
:global(.oofbbnecl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-6 4.889V13h2.667l.889 2.222l-1.334 1.334l2.222 2.222l1.334-1.334l2.222.89V21h-.889A7.11 7.11 0 0 1 13 13.889");
}

</style>
