<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="bsx0s_bjj"/><path class="rni-g5kma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-system-update" {...props}></Icon>
<style>
:global(.bsx0s_bjj) {
  width: 25.525px;
  height: 39px;
  x: 11.237px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.rni-g5kma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.858 30.12V14.748l5.456 5.884m-5.456-5.884l-5.456 5.884m-7.165 17.555h25.526");
}

</style>
