<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="vq_7155oo"/><path class="no-1hpzxm"/><path class="cna8012ch"/><path class="nnwao2bjn"/><path class="tfzdxif4b"/><path class="kbcu0ebrl"/><path class="fg8libqda"/><path class="pw61xnbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ab-test-duotone-bold" {...props}></Icon>
<style>
:global(.cna8012ch) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 10 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fg8libqda) {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jz0b4rbqp) {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kbcu0ebrl) {
  d: path("m12 10 6 6");
}

:global(.nnwao2bjn) {
  d: path("M12 3v7");
}

:global(.no-1hpzxm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 10 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.st2iv5bfu) {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tfzdxif4b) {
  d: path("m12 10 -6 6");
}

:global(.vq_7155oo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
