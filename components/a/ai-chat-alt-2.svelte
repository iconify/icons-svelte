<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="w5un1bcyv"/><ellipse transform="rotate(-60 24 24)" class="w5un1bcyv"/><ellipse transform="rotate(-30 24 24)" class="vb_vbgbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ai-chat-alt-2" {...props}></Icon>
<style>
:global(.vb_vbgbqn) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.5px;
  ry: 7.5px;
}

:global(.w5un1bcyv) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.5px;
  ry: 20.5px;
}

</style>
