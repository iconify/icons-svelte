<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ee3sz8y1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:reverse-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.ee3sz8y1c) {
  fill: var(--svg-color--fff, #fff);
  d: path("M38 12L18 32l20 20z");
}

</style>
