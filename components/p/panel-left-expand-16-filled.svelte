<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="kd4jlifea"/><path class="gkr0c5blq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-left-expand-16-filled" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gkr0c5blq) {
  d: path("M2 4.999a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6.002a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm10-1H7v8.002h5a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1");
}

:global(.kd4jlifea) {
  d: path("M8.5 7.5h1.791l-.646-.646a.5.5 0 0 1 .707-.707l1.5 1.5a.5.5 0 0 1 0 .707l-1.5 1.5a.5.5 0 1 1-.707-.707l.646-.647H8.5a.5.5 0 0 1 0-1");
}

</style>
