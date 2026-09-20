<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k03z74m2p"/><path class="s3jkkrb6o"/><path class="dbb3ymiyd"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:first-aid-kit-duotone-regular" {...props}></Icon>
<style>
:global(.dbb3ymiyd) {
  d: path("M9 7V4h6v3");
}

:global(.k03z74m2p) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s3jkkrb6o) {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
