<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="xi2fzfb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:right-arrow" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.xi2fzfb3w) {
  fill: var(--svg-color--fff, #fff);
  d: path("M33.7 16L49 32L33.7 48V37.4H15V27.1h18.7z");
}

</style>
