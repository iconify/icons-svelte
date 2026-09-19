<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="rcpk3abwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:circled-m" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.rcpk3abwx) {
  fill: var(--svg-color--fff, #fff);
  d: path("m41 15l-9 9l-9-9h-6v34h6V24l9 9l9-9v25h6V15z");
}

</style>
