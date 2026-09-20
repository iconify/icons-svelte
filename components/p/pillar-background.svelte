<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="agix0bcxn"/><path class="nyvdh3bby"/><path class="lqrp8i-lb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pillar-background" {...props}></Icon>
<style>
:global(.agix0bcxn) {
  fill: var(--svg-color--9601d9, #9601d9);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lqrp8i-lb) {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.473 6H6.4v4h4.073z");
}

:global(.nyvdh3bby) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.454 20L6.4 17v-3h8.145V4L17.6 7v10H9.454z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
