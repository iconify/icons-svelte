<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="b93v0obyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nda-document-sharp" {...props}></Icon>
<style>
:global(.b93v0obyy) {
  d: path("M7.75 5.5h8.5V8h-8.5zm0 5.5h8.5m-8.5 3h5.5v2.5h-5.5z");
}

:global(.bh4biibbp) {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
