<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cv160nt7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bed-fill" {...props}></Icon>
<style>
:global(.cv160nt7x) {
  fill: currentColor;
  d: path("M216 72H32V48a8 8 0 0 0-16 0v160a8 8 0 0 0 16 0v-32h208v32a8 8 0 0 0 16 0v-96a40 40 0 0 0-40-40M32 88h72v72H32Z");
}

</style>
