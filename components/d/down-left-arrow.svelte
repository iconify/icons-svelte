<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="negmfpbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:down-left-arrow" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.negmfpbdb) {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.1 44.5L20 44l-.5-22.1l7.5 7.5l13.2-13.3l7.3 7.3l-13.3 13.2z");
}

</style>
