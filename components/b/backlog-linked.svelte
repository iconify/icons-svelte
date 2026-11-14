<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkvpeebao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:backlog-linked" {...props}></Icon>
<style>
:global(.jkvpeebao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H14v7H2.5Zm0 11H14v7H2.5ZM17 3h4.5v8H17Zm2.25 6v6M17 13h4.5v8H17Z");
}

</style>
