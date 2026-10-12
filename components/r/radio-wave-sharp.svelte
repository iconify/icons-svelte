<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f983zhbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:radio-wave-sharp" {...props}></Icon>
<style>
:global(.f983zhbuf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12q2.31-7.995 4.62 0c2.31 7.995 3.08 5.33 4.63 0s3.08-5.33 4.62 0s3.08 5.33 4.63 0");
}

</style>
