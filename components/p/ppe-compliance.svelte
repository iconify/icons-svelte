<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e53g5accw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ppe-compliance" {...props}></Icon>
<style>
:global(.e53g5accw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12.5a7.5 7.5 0 0 1 15 0M12.8 16H2.5v-3.5h17.8M12 5v4m2.75 9l2 2L21 15.75");
}

</style>
