<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dnc3sobep"/><rect class="bs8yprwkr"/><path class="qq9xalbip"/><path class="jt9wyzbdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ransomware" {...props}></Icon>
<style>
:global(.bs8yprwkr) {
  width: 7px;
  height: 5.5px;
  x: 8.5px;
  y: 12.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

:global(.dnc3sobep) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.75H14L19.25 8v11.5a1.75 1.75 0 0 1-1.75 1.75h-11a1.75 1.75 0 0 1-1.75-1.75v-15A1.75 1.75 0 0 1 6.5 2.75");
}

:global(.jt9wyzbdh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.25h.01");
}

:global(.qq9xalbip) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12.5V8.75a2 2 0 0 1 4 0v1");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
