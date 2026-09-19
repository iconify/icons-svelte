<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ad7e00btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:down-arrow" {...props}></Icon>
<style>
:global(.ad7e00btn) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 33.7L32 49l16-15.3H37.4V15H27.1v18.7z");
}

:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
