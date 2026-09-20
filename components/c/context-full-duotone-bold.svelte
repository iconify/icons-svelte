<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="qude_sb_h"/><path class="kkvfu5bre"/><path class="hw-0_-irv"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="y5k8b5bfa"/><path class="l517yxbln"/><path class="coi-np7dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-full-duotone-bold" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.coi-np7dk) {
  d: path("M15 9v6");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.hw-0_-irv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kkvfu5bre) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.lx3jyybfn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qude_sb_h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x87wa6b5t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y5k8b5bfa) {
  d: path("M9 9v6");
}

</style>
