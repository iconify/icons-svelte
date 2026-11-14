<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njxz2cbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:basil-plant" {...props}></Icon>
<style>
:global(.njxz2cbbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5v-18M12 16c-3 1-8-.5-8.5-4.5c4-.5 7.5 1 8.5 4.5Zm0 0c3 1 8-.5 8.5-4.5c-4-.5-7.5 1-8.5 4.5Zm0-7.5c-2 .5-5.5-.5-6-4c3-.5 5.5 1 6 4Zm0 0c2 .5 5.5-.5 6-4c-3-.5-5.5 1-6 4Z");
}

</style>
