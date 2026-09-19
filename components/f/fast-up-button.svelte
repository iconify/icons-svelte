<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="u_old8bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:fast-up-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.u_old8bea) {
  fill: var(--svg-color--fff, #fff);
  d: path("M50 46L38.1 33.3H50L32 14L14 33.3h11.9L14 46z");
}

</style>
