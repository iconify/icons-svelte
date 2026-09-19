<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibek2co3k"/><path class="o2srxbcsm"/><path class="ec58tkbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:remotefiles" {...props}></Icon>
<style>
:global(.ec58tkbjm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.92 4.5v9.3h9.61");
}

:global(.ibek2co3k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.78 43.5l-5.25-4.56l5.25-4.64m3.58-12.07l5.25 4.56l-5.25 4.64m5.25-4.64H9.47");
}

:global(.o2srxbcsm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.53 39h24a2 2 0 0 0 2-2V13.8l-9.28-9.28H14.58a2.05 2.05 0 0 0-2.05 2.05v12.55");
}

</style>
