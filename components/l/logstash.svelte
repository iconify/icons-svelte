<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":307};
const content = `<path class="l98oocv4j"/><path class="mjpfvkdiu"/><path class="h6jxh2b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:logstash" {...props}></Icon>
<style>
:global(.h6jxh2b1g) {
  fill: var(--svg-color--00bfb3, #00bfb3);
  d: path("M150.261 306.086H256V189.217H150.261z");
}

:global(.l98oocv4j) {
  fill: var(--svg-color--fec514, #fec514);
  d: path("M122.435 189.217H0V0h11.13c61.474 0 111.305 49.83 111.305 111.304z");
}

:global(.mjpfvkdiu) {
  fill: var(--svg-color--343741, #343741);
  d: path("M116.87 306.086h5.565V189.217H0c0 64.545 52.324 116.87 116.87 116.87");
}

</style>
