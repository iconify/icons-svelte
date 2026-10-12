<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7zrksbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:perspective" {...props}></Icon>
<style>
:global(.i7zrksbiv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5.5h7q1.5 0 1.97 1.43l3.31 10.14q.47 1.43-1.03 1.43H4.25q-1.5 0-1.03-1.43L6.53 6.93Q7 5.5 8.5 5.5m1.83 0l-1.41 13m4.75-13l1.41 13");
}

</style>
