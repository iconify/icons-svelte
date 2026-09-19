<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="fcq8r33rh"/><g class="n1mjunbsu"><path class="k2w4k3b6j"/><path class="fy2f6b59n"/><circle class="xq6jaeb2t"/></g><circle class="uzm2mooko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:four-oclock" {...props}></Icon>
<style>
:global(.fcq8r33rh) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--62727a, #62727a);
}

:global(.fy2f6b59n) {
  d: path("m26 30.6l1.9-3.6L48 39.4L46.1 43z");
}

:global(.k2w4k3b6j) {
  d: path("M30 6h4v32h-4z");
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.uzm2mooko) {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--62727a, #62727a);
}

:global(.xq6jaeb2t) {
  cx: 32px;
  cy: 32px;
  r: 4px;
}

</style>
