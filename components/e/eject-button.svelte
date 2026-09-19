<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="kp2nsvpkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:eject-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.kp2nsvpkr) {
  fill: var(--svg-color--fff, #fff);
  d: path("m16 33.6l16-19l16 19zm0 4h32v5.7H16z");
}

</style>
