<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rncaisbya"/><path class="bqqmp9bon"/><path class="a1z8vac9r"/><path class="yzk-0x3pl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deadlock-outline-regular" {...props}></Icon>
<style>
:global(.a1z8vac9r) {
  d: path("M17.5 16H22");
}

:global(.bqqmp9bon) {
  d: path("M6.5 5.5 9 8l-2.5 2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rncaisbya) {
  d: path("M2 8h4.5");
}

:global(.yzk-0x3pl) {
  d: path("M17.5 13.5 15 16l2.5 2.5");
}

</style>
