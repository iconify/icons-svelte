<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esk_72bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:desiccator" {...props}></Icon>
<style>
:global(.esk_72bix) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 14v-2a7.5 7.5 0 0 1 15 0v2M12 4.5v-2M2.5 14h19m-17 0L6 21h12l1.5-7m-11 3.5h7");
}

</style>
