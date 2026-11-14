<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tyev_0jvj"/><path class="l76l-6b7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lazy-load" {...props}></Icon>
<style>
:global(.l76l-6b7v) {
  d: path("m8 12.75l4 4l4-4");
}

:global(.tyev_0jvj) {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12m.75-3.75h.01m1.99-3h.01m2.99-2h.01M12 7v9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
