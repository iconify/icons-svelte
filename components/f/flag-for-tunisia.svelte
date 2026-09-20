<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="udceh8b_r"/><circle class="w59zm0bso"/><path class="r33rdbbws"/><path class="cqrmd_bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-tunisia" {...props}></Icon>
<style>
:global(.cqrmd_bxn) {
  fill: var(--svg-color--e70013, #E70013);
  d: path("M19.645 16.937l-1.249-1.719v2.125L16.375 18l2.021.657v2.125l1.249-1.719l2.021.656L20.417 18l1.249-1.719z");
}

:global(.r33rdbbws) {
  fill: var(--svg-color--e70013, #E70013);
  d: path("M15.4 18a3.9 3.9 0 0 1 6.541-2.869a4.875 4.875 0 1 0 0 5.738A3.9 3.9 0 0 1 15.4 18z");
}

:global(.udceh8b_r) {
  fill: var(--svg-color--e70013, #E70013);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

:global(.w59zm0bso) {
  fill: var(--svg-color--fff, #FFF);
  cx: 18px;
  cy: 18px;
  r: 6.5px;
}

</style>
