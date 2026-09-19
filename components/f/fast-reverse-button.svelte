<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="h2izat9ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:fast-reverse-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.h2izat9ej) {
  fill: var(--svg-color--fff, #fff);
  d: path("M44.1 14L31.3 25.9V14L11.9 32l19.4 18V38.1L44.1 50z");
}

</style>
