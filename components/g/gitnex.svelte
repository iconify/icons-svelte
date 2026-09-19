<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="pqn6sdbdg"/><circle class="hkguhzaue"/><circle class="hlrjrz1pv"/><circle class="vyy84nbsk"/><circle class="iu_m9tbwx"/><path class="ly68tyyti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gitnex" {...props}></Icon>
<style>
:global(.hkguhzaue) {
  cx: 12.27px;
  cy: 12.4px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hlrjrz1pv) {
  cx: 35.73px;
  cy: 12.4px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iu_m9tbwx) {
  cx: 24px;
  cy: 26.11px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ly68tyyti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.27 8.76V4.5m0 11.54v20.18m23.46 0V16.04M15.91 12.4H19a5 5 0 0 1 5 5v5.07m0 7.28v5.11a5 5 0 0 0 5 5h3.09");
}

:global(.pqn6sdbdg) {
  cx: 12.27px;
  cy: 39.86px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vyy84nbsk) {
  cx: 35.73px;
  cy: 39.86px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
