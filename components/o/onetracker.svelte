<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="uh-iufbpq"/><circle class="p_y1_xb_g"/><path class="n9nhogtxr"/><path class="h6wukccmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:onetracker" {...props}></Icon>
<style>
:global(.h6wukccmc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.272 18.662v6.744h6.744V20.74l-2.529-2.08zm-25.4.675h10.733M6.467 23.1h10.059M4.5 26.923h10.733");
}

:global(.n9nhogtxr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.814 32.318H43.5V19.73l-5.676-4.72H30.07m2.528 17.308H22.146m-10.172 0H9.277v-3.372m0-11.801v-6.07h20.792v21.243");
}

:global(.p_y1_xb_g) {
  cx: 37.171px;
  cy: 33.914px;
  r: 3.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.uh-iufbpq) {
  cx: 17.06px;
  cy: 33.914px;
  r: 3.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
