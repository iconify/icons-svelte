<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqxc61b9f"/><path class="zumcy7bta"/><path class="kdztqobrs"/><path class="nfxrlh6dt"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="pty_wsbvs"/><path class="lnqk7fb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rest-endpoint-duotone-bold" {...props}></Icon>
<style>
:global(.jroakeb3a) {
  d: path("M17 4h4v16h-4");
}

:global(.kdztqobrs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnqk7fb0y) {
  d: path("M8 15h5");
}

:global(.nfxrlh6dt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqxc61b9f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.to02llleg) {
  d: path("M7 4H3v16h4");
}

:global(.zumcy7bta) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
