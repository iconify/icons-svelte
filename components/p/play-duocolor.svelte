<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5b5z48vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-duocolor" {...props}></Icon>
<style>
:global(.c5b5z48vm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.029 4.285l10 6c1.295.777 1.295 2.653 0 3.43l-10 6C7.696 20.515 6 19.555 6 18V6c0-1.555 1.696-2.515 3.029-1.715");
}

</style>
