<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="fsm18xluf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:left-arrow" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.fsm18xluf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M30.3 16L15 32l15.3 16V37.4H49V27.1H30.3z");
}

</style>
