<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzyaeegyg"/><path class="jbx312dhc"/><circle class="awuipgffp"/><path class="fntodxa3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-save-all" {...props}></Icon>
<style>
:global(.awuipgffp) {
  cx: 13.5px;
  cy: 15.5px;
  r: 2.5px;
  fill: currentColor;
}

:global(.fntodxa3b) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h10v2H4v10H2z");
}

:global(.jbx312dhc) {
  fill: currentColor;
  d: path("M9 9h6v2H9z");
}

:global(.pzyaeegyg) {
  fill: currentColor;
  d: path("M17 6H8a2 2 0 0 0-2 2v11a2 2 0 0 0 2 2h11c1.1 0 2-.9 2-2v-9zm2 13H8V8h8.17L19 10.83z");
}

</style>
