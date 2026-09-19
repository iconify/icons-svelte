<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ev1q9olqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:letter-t" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.ev1q9olqn) {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.8 17.5v5.1h-8.7v23.9H29V22.6h-8.7v-5.1z");
}

</style>
