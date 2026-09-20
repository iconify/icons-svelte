<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k38v4qb6f"/><path class="wo--el8ej"/><path class="w2kj39b7f"/><path class="d0m2khbql"/><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="gnhsdzb8d"/><path class="elmoo_bpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:payslip-duotone-regular" {...props}></Icon>
<style>
:global(.d0m2khbql) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.elmoo_bpw) {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gnhsdzb8d) {
  d: path("M6 13h6");
}

:global(.k38v4qb6f) {
  fill: currentColor;
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ky4omnbla) {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w2kj39b7f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wo--el8ej) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zwh7a2bjz) {
  d: path("M6 9h9");
}

</style>
