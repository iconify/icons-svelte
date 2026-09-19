<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="wl5p9fbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:play-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.wl5p9fbiw) {
  fill: var(--svg-color--fff, #fff);
  d: path("m25 12l20 20l-20 20z");
}

</style>
