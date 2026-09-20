<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eyho-ybbg"/><path class="r51x54r8q"/><path class="ufppdlbpv"/><path class="uh5a45b0l"/><path class="tt1n5wbag"/><path class="l8unaacgj"/><path class="e3aed6d4j"/><path class="pfpu_3ppl"/><path class="wskxlyzso"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delay-duotone-regular" {...props}></Icon>
<style>
:global(.e3aed6d4j) {
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
}

:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.eyho-ybbg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8unaacgj) {
  d: path("M2 12h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.r51x54r8q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tt1n5wbag) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ufppdlbpv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uh5a45b0l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wskxlyzso) {
  d: path("M12 12h3");
}

</style>
