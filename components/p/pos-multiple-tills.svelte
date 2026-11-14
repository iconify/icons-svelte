<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xvg66jk0e"/><path class="mp362um3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-multiple-tills" {...props}></Icon>
<style>
:global(.mp362um3e) {
  d: path("M9 5v-.5a2 2 0 0 1 2-2h8.5a2 2 0 0 1 2 2V8a2 2 0 0 1-2 2h-4m2.25 0v9m-3.25 0H21v2.5h-6.5Zm-9.25-8.75h4m-4 2.5h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xvg66jk0e) {
  d: path("M2.5 7h11v8h-11ZM8 15v4m-4 0h8v2.5H4Z");
}

</style>
