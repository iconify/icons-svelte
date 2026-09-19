<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="df7qmgmhn"/><path class="w8i9pu2fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:discovery" {...props}></Icon>
<style>
:global(.df7qmgmhn) {
  cx: 16.239px;
  cy: 28.435px;
  r: 11.739px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.w8i9pu2fa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.24 16.696v-8.87h11.086A16.174 16.174 0 0 1 43.5 24h0a16.174 16.174 0 0 1-16.174 16.174H16.24");
}

</style>
