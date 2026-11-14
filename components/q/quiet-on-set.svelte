<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic4enj5nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:quiet-on-set" {...props}></Icon>
<style>
:global(.ic4enj5nw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 3.5h13.1v13.1m-3.9 3.9H3.5V7.4m0 1.6h1.6m7.8 0h7.6M8 3.5l.342.94M13.5 3.5l2 5.5m-12-5.5l17 17");
}

</style>
