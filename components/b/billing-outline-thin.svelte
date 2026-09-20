<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/><path class="x3sflacnk"/><path class="uesvxd39h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:billing-outline-thin" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.aum97lbyp) {
  d: path("M9 13h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.uesvxd39h) {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.x3sflacnk) {
  d: path("M9 18h6");
}

</style>
