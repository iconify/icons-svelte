<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf-nehcvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pitchers-mound" {...props}></Icon>
<style>
:global(.tf-nehcvq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5c4 0 4.5-10 7.5-10h4c3 0 3.5 10 7.5 10ZM10 5.75h4");
}

</style>
