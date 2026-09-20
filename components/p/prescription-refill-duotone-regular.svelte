<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d71dwlbpe"/><path class="k9od9gkcz"/><path class="fbrxx_p0f"/><path class="xfirob-xp"/><path class="t-ht_no5g"/><path class="gcalxb98a"/><path class="ckrzk6zny"/><path class="qtxvlht3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prescription-refill-duotone-regular" {...props}></Icon>
<style>
:global(.ckrzk6zny) {
  d: path("M10.5 10.5 8 13l2.5 2.5");
}

:global(.d71dwlbpe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3h14l4 4v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fbrxx_p0f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 10.5 8 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.k9od9gkcz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 13h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.t-ht_no5g) {
  d: path("M4 3h14l4 4v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.xfirob-xp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
