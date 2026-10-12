<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcnyf-bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:direct-debit-sharp" {...props}></Icon>
<style>
:global(.rcnyf-bmu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h14v10.5h-14zm0 4h14m-8.5 8.75V19h12.5m-2.25-2.25L20.75 19l-2.25 2.25");
}

</style>
