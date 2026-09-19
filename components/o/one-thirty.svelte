<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="fcq8r33rh"/><g class="n1mjunbsu"><circle class="xq6jaeb2t"/><path class="a2o09kb0k"/><path class="td4xvxbtu"/></g><circle class="uzm2mooko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:one-thirty" {...props}></Icon>
<style>
:global(.a2o09kb0k) {
  d: path("M30 26h4v32h-4z");
}

:global(.fcq8r33rh) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--62727a, #62727a);
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.td4xvxbtu) {
  d: path("m26.035 35.15l17.102-17.122l2.83 2.827l-17.102 17.121z");
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
