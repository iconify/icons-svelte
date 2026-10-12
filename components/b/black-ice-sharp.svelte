<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-d71bbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:black-ice-sharp" {...props}></Icon>
<style>
:global(.o-d71bbye) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 2.75l-4.25 18.5M15 2.75l4.25 18.5M12 3.5V7m0 4.75v6m2.6-4.5l-5.2 3m5.2 0l-5.2-3");
}

</style>
