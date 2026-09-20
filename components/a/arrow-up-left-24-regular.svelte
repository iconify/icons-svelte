<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsup8i38a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-left-24-regular" {...props}></Icon>
<style>
:global(.jsup8i38a) {
  fill: currentColor;
  d: path("M13.246 3a.75.75 0 0 1 0 1.5H5.577l15.2 15.2a.765.765 0 0 1-1.082 1.081L4.496 5.581v7.669a.75.75 0 0 1-1.5 0v-9.5a.75.75 0 0 1 .75-.75z");
}

</style>
