<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjwk3x5es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:big-button-switch-sharp" {...props}></Icon>
<style>
:global(.zjwk3x5es) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25h.75a6.5 6.5 0 0 1 13 0h2.75v6H2.75v-6zm.75 0h13M12 2.75V6.5m-2-2l2 2l2-2");
}

</style>
