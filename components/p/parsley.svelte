<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbkyklb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parsley" {...props}></Icon>
<style>
:global(.lbkyklb7y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5v-13m0 9L6 15m6 2.5l6-2.5m-7.5-6.5a2 2 0 0 1-1-3.5a2.5 2.5 0 0 1 5 0a2 2 0 0 1-1 3.5Zm-6 6.5a2 2 0 0 1-1-3.5a2.5 2.5 0 0 1 5 0a2 2 0 0 1-1 3.5Zm12 0a2 2 0 0 1-1-3.5a2.5 2.5 0 0 1 5 0a2 2 0 0 1-1 3.5Z");
}

</style>
