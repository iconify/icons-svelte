<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="jfrttcclg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:fast-down-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.jfrttcclg) {
  fill: var(--svg-color--fff, #fff);
  d: path("m14 18l11.9 12.7H14L32 50l18-19.3H38.1L50 18z");
}

</style>
