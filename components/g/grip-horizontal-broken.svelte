<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="zo874nbdq"/><circle class="xnbezkb7w"/><circle class="lekigjbvy"/><circle class="hzbwlrnku"/><circle class="mqy674b1p"/><circle class="f3sty6bdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grip-horizontal-broken" {...props}></Icon>
<style>
:global(.f3sty6bdo) {
  cx: 19px;
  cy: 8.488px;
  r: 0.75px;
}

:global(.hzbwlrnku) {
  cx: 5px;
  cy: 8.504px;
  r: 0.75px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lekigjbvy) {
  cx: 19px;
  cy: 15.496px;
  r: 0.75px;
}

:global(.mqy674b1p) {
  cx: 12px;
  cy: 8.504px;
  r: 0.75px;
}

:global(.xnbezkb7w) {
  cx: 12px;
  cy: 15.512px;
  r: 0.75px;
}

:global(.zo874nbdq) {
  cx: 5px;
  cy: 15.512px;
  r: 0.75px;
}

</style>
