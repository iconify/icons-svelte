<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7q-h7bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flood-depth-gauge" {...props}></Icon>
<style>
:global(.e7q-h7bxa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V16m0-10.5h4.5M12 9h3m-3 3.5h4.5M2.5 16c1.5-1.5 3.25-1.5 4.75 0s3.25 1.5 4.75 0s3.25-1.5 4.75 0s3.25 1.5 4.75 0m-19 4.5C4 19 5.75 19 7.25 20.5s3.25 1.5 4.75 0s3.25-1.5 4.75 0s3.25 1.5 4.75 0");
}

</style>
