<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5hydcdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:edgesensor-low-sharp" {...props}></Icon>
<style>
:global(.jw5hydcdb) {
  fill: currentColor;
  d: path("M4.23 13.5v-6h1v6zm14.54 3v-6h1v6zM6.807 20V4h10.384v16zm5.78-11.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
