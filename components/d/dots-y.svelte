<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="lwivuzb_u"/><circle class="ehbqml5ic"/><circle class="m_cyn06nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:dots-y" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ehbqml5ic) {
  cx: 10px;
  cy: 10px;
  r: 2px;
}

:global(.lwivuzb_u) {
  cx: 10px;
  cy: 15px;
  r: 2px;
}

:global(.m_cyn06nd) {
  cx: 10px;
  cy: 5px;
  r: 2px;
}

</style>
