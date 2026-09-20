<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o48nut9qz"/><path class="omcxz1ygw"/><path class="tg5bh2bez"/><path class="vikxbrwks"/><path class="z-klfibmd"/><path class="ils7yp4cg"/><path class="uk0rveqaj"/><path class="rdx5t34om"/><path class="r09np9bwl"/><path class="rj62dp6ok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:message-bus-duotone-regular" {...props}></Icon>
<style>
:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o48nut9qz) {
  fill: currentColor;
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.omcxz1ygw) {
  fill: currentColor;
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r09np9bwl) {
  d: path("M6 9.5V16");
}

:global(.rdx5t34om) {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rj62dp6ok) {
  d: path("M18 9.5V16");
}

:global(.tg5bh2bez) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vikxbrwks) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9.5V16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z-klfibmd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 9.5V16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
