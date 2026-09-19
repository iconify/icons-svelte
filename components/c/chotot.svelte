<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i8tkc-bvy"/><path class="vt-3_bala"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chotot" {...props}></Icon>
<style>
:global(.i8tkc-bvy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.713 35.828a5.45 5.45 0 0 1-4.53-6.236l.868-5.485a5.45 5.45 0 0 1 10.767 1.706l-.87 5.484a5.45 5.45 0 0 1-6.235 4.53ZM4.5 19.509h10.9M7.555 35.786L9.95 19.51m22.65-.001h10.9m-7.846 16.277l2.395-16.277");
}

:global(.vt-3_bala) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.363 28.24l.993 2.37l4.28-5.817m-3.309-8.986l2.414-1.234l2.029 1.234m1.234-2.468l3.649-1.235");
}

</style>
