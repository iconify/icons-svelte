<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v_7knkbwn"/><circle class="lygk6dbzl"/><path class="jqncicmjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magic-staff-sharp" {...props}></Icon>
<style>
:global(.jqncicmjh) {
  d: path("m7 4l.3 2.2l2.2.3l-2.2.3L7 9l-.3-2.2l-2.2-.3l2.2-.3z");
}

:global(.lygk6dbzl) {
  cx: 16.5px;
  cy: 7.5px;
  r: 3px;
}

:global(.v_7knkbwn) {
  d: path("M3.75 20.25L14.38 9.62");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
