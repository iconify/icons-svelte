<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><circle class="azhp-xb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:record-button" {...props}></Icon>
<style>
:global(.azhp-xb4t) {
  cx: 32px;
  cy: 32px;
  r: 15px;
  fill: var(--svg-color--fff, #fff);
}

:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
