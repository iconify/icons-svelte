<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="k2fqt0oli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:antenna-bars" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.k2fqt0oli) {
  fill: var(--svg-color--fff, #fff);
  d: path("M44 16h6v32h-6zm-10 8h6v24h-6zm-10 8h6v16h-6zm-10 8h6v8h-6z");
}

</style>
