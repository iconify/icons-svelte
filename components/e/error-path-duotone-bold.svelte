<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hz31h062l"/><path class="xiouf5t6o"/><path class="y5h-cjygw"/><path class="v1lpksb8n"/><path class="akm88w1ho"/><path class="v_3erbqcl"/><path class="c05571vet"/><path class="puhwuz9ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:error-path-duotone-bold" {...props}></Icon>
<style>
:global(.akm88w1ho) {
  d: path("M2 8h7l4 4h9");
}

:global(.c05571vet) {
  d: path("m16 15 4 4");
}

:global(.hz31h062l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h7l4 4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.puhwuz9ig) {
  d: path("m20 15 -4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v_3erbqcl) {
  d: path("m9 8 4 -4h9");
}

:global(.v1lpksb8n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 15 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xiouf5t6o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 8 4 -4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y5h-cjygw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 15 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
