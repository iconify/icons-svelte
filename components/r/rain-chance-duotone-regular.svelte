<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="esolkqbpc"/><path class="d63c1ws2f"/><path class="hrg1ozfca"/><path class="c-pcdbceg"/><path class="dn5wogbzl"/><path class="qxclf1btn"/><path class="olx0yluil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rain-chance-duotone-regular" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.d63c1ws2f) {
  fill: currentColor;
  d: path("M7.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dn5wogbzl) {
  d: path("M7.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.esolkqbpc) {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hrg1ozfca) {
  fill: currentColor;
  d: path("M12.5 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.olx0yluil) {
  d: path("M12.5 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qxclf1btn) {
  d: path("m8 21 6 -6");
}

</style>
