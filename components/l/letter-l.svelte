<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="l7_u9bb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:letter-l" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.l7_u9bb3w) {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.7 17.5h6.1v23.8h14.5v5.2H22.7z");
}

</style>
