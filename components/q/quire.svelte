<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ckbus-mzh"/><path class="sk6ofjbop"/><path class="t_u7axbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:quire" {...props}></Icon>
<style>
:global(.ckbus-mzh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.338 36.908a17.108 17.108 0 1 1 4.904-23.692");
}

:global(.sk6ofjbop) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.302 21.099c-.16 8.45 20.036 7.827 18.81 21.401");
}

:global(.t_u7axbqw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.243 13.216a17.11 17.11 0 0 1-.117 18.971");
}

</style>
