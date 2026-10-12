<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yip3ogbix"/><circle class="qcyv72b4r"/><path class="nendhobqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diwali-rangoli" {...props}></Icon>
<style>
:global(.nendhobqh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 12h.01M12 18.25h.01M5.75 12h.01M12 5.75h.01");
}

:global(.qcyv72b4r) {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yip3ogbix) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 12a4.6 4.6 0 0 1 7 0a4.6 4.6 0 0 1-7 0M12 14.25a4.6 4.6 0 0 1 0 7a4.6 4.6 0 0 1 0-7M9.75 12a4.6 4.6 0 0 1-7 0a4.6 4.6 0 0 1 7 0M12 9.75a4.6 4.6 0 0 1 0-7a4.6 4.6 0 0 1 0 7m2.83 5.08a3.5 3.5 0 0 1 2.47 2.47a3.5 3.5 0 0 1-2.47-2.47m-5.66 0A3.5 3.5 0 0 1 6.7 17.3a3.5 3.5 0 0 1 2.47-2.47m0-5.66A3.5 3.5 0 0 1 6.7 6.7a3.5 3.5 0 0 1 2.47 2.47m5.66 0A3.5 3.5 0 0 1 17.3 6.7a3.5 3.5 0 0 1-2.47 2.47");
}

</style>
