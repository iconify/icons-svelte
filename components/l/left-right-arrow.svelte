<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ez8ijy23w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:left-right-arrow" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.ez8ijy23w) {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 32l15.5 16V36.6h9V48L52 32L36.5 16v11.4h-9V16z");
}

</style>
