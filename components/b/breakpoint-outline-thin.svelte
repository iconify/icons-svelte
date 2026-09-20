<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7d250moc"/><path class="tee3b-ble"/><path class="jlpxneb5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:breakpoint-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlpxneb5g) {
  d: path("M9 8v8");
}

:global(.n7d250moc) {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.tee3b-ble) {
  d: path("M10 12h11");
}

</style>
