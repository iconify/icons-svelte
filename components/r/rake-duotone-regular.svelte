<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gxecv1bcc"/><path class="ni3lnewqa"/><path class="acpdoe2mm"/><path class="rmhm9l1ql"/><path class="oxd1nqbfa"/><path class="pdai76vlu"/><path class="qv6cnabrq"/><path class="oqj-o0b2r"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="zpusjcvvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rake-duotone-regular" {...props}></Icon>
<style>
:global(.acpdoe2mm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.evsu0jbbm) {
  d: path("M10 14v4");
}

:global(.gxecv1bcc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ktxjg3b2q) {
  d: path("M6 14v4");
}

:global(.ni3lnewqa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.oxd1nqbfa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pdai76vlu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qv6cnabrq) {
  d: path("M12 3v11");
}

:global(.rmhm9l1ql) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpusjcvvn) {
  d: path("M18 14v4");
}

</style>
