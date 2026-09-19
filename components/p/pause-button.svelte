<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="z5pnvwbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:pause-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.z5pnvwbbk) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 14h8v36h-8zm16 0h8v36h-8z");
}

</style>
