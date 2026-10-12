<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c824zd04j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:plateau-sharp" {...props}></Icon>
<style>
:global(.c824zd04j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.16 12.09l1.68-3.68l.41-.91h13.5l.41.91l1.68 3.68l.41.91H2.75zm-.41 6.41c2-1.6 4.17-1.6 6.17 0s4.17 1.6 6.17 0s4.16-1.6 6.16 0");
}

</style>
