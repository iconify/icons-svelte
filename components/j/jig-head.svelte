<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g9g9ukj4h"/><path class="hwgexh1nq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:jig-head" {...props}></Icon>
<style>
:global(.g9g9ukj4h) {
  d: path("M3 11.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

:global(.hwgexh1nq) {
  d: path("M5.75 5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 11.5h5.5a3.5 3.5 0 0 1 0 7H15v-3m-7.5-4h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
