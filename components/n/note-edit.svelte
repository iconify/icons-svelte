<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="upbcgobek"/><path class="nmt-o11bm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:note-edit" {...props}></Icon>
<style>
:global(.nmt-o11bm) {
  d: path("M14 20v-4a2 2 0 0 1 2-2h4m-6.879-7.036l1.415 1.415l-4.597 4.596l-1.767.353l.353-1.767Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.upbcgobek) {
  d: path("M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8l-6 6H6a2 2 0 0 1-2-2Z");
}

</style>
