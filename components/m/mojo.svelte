<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(30 10.982 24)" class="lb0o4p8oz"/><rect transform="rotate(30 24 24)" class="lwvtzxb4a"/><rect transform="rotate(30 37.018 24)" class="kvqcm7bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mojo" {...props}></Icon>
<style>
:global(.kvqcm7bky) {
  width: 7.611px;
  height: 18.33px;
  x: 33.212px;
  y: 14.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.806px;
  ry: 3.806px;
}

:global(.lb0o4p8oz) {
  width: 7.611px;
  height: 18.33px;
  x: 7.177px;
  y: 14.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.806px;
  ry: 3.806px;
}

:global(.lwvtzxb4a) {
  width: 7.611px;
  height: 18.33px;
  x: 20.194px;
  y: 14.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.806px;
  ry: 3.806px;
}

</style>
