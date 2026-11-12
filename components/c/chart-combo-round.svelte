<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0sirkblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-combo-round" {...props}></Icon>
<style>
:global(.q0sirkblq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16v4m6-6v6m6-8v8M3 4v12a4 4 0 0 0 4 4h14M3 11l4-4c1.163-1.163 3.256-1.163 5 0s3.837 1.163 5 0l4-4");
}

</style>
