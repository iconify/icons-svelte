<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="ozrrc3b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:letter-k" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.ozrrc3b-o) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.2 17.5h6v12l11.2-12h7.8L33.3 29.4l12.5 17.1H38l-8.9-12.7l-2.9 3v9.7h-6z");
}

</style>
