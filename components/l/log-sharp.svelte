<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vo1yiebru"/><path class="zlbxh0rej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:log-sharp" {...props}></Icon>
<style>
:global(.vo1yiebru) {
  d: path("M6 7h15.25v10H6A3.25 5 0 0 1 6 7Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zlbxh0rej) {
  d: path("M6 7a3.25 5 0 0 1 0 10A3.25 5 0 0 1 6 7Zm0 3.5a.9 1.5 0 0 0 0 3a.9 1.5 0 0 0 0-3Zm5.5-.25h5m-3 3.5h5");
}

</style>
