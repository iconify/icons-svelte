<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ii5vybbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:fast-forward-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.ii5vybbbu) {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.9 14l12.8 11.9V14l19.4 18l-19.4 18V38.1L19.9 50z");
}

</style>
