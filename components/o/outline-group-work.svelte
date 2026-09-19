<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsfw75g9a"/><circle class="kgneaxreo"/><circle class="x621cbc6b"/><circle class="czwmjhe3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-group-work" {...props}></Icon>
<style>
:global(.czwmjhe3n) {
  cx: 16px;
  cy: 14px;
  r: 2px;
  fill: currentColor;
}

:global(.kgneaxreo) {
  cx: 8px;
  cy: 14px;
  r: 2px;
  fill: currentColor;
}

:global(.x621cbc6b) {
  cx: 12px;
  cy: 8px;
  r: 2px;
  fill: currentColor;
}

:global(.zsfw75g9a) {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

</style>
