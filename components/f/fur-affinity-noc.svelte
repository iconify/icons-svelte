<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="zreh_jbxm"/><ellipse class="ueqq13bxa"/><ellipse transform="rotate(-85.42 37.039 17.585)" class="scovbbcpb"/><ellipse transform="rotate(-4.58 10.961 17.584)" class="uuqfk4bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fur-affinity-noc" {...props}></Icon>
<style>
:global(.scovbbcpb) {
  cx: 37.039px;
  cy: 17.585px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.066px;
  ry: 5.449px;
}

:global(.ueqq13bxa) {
  cx: 23.915px;
  cy: 13.861px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.449px;
  ry: 7.447px;
}

:global(.uuqfk4bwi) {
  cx: 10.961px;
  cy: 17.585px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.449px;
  ry: 7.066px;
}

:global(.zreh_jbxm) {
  cx: 23.915px;
  cy: 32.457px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.464px;
  ry: 9.129px;
}

</style>
