<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="hyjdh9sba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:letter-y" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.hyjdh9sba) {
  fill: var(--svg-color--fff, #fff);
  d: path("M38 17.5h6.9l-9.7 18.1v10.9h-6.1V35.6l-10-18.1h7.1l6 12.6z");
}

</style>
