<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="tp7zmcblf"/><path class="kfqvosbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:joe" {...props}></Icon>
<style>
:global(.kfqvosbcv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24a6.488 6.488 0 1 0 12.975 0v-6.488M43.5 24a6.488 6.488 0 1 1-1.9-4.588l-9.175 9.176");
}

:global(.tp7zmcblf) {
  cx: 23.956px;
  cy: 24px;
  r: 6.488px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
