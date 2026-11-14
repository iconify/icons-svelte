<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otldlnbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blast-fence" {...props}></Icon>
<style>
:global(.otldlnbuc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 18V5l2-2l2 2l2-2l2 2l2-2l2 2v13M6.5 18h15v3.5h-15ZM12 5v13m4-13v13M2.5 7l2.75 2M2.5 11.5l2.75 2");
}

</style>
