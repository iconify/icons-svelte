<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq19zibfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-sensor-lo-outline-sharp" {...props}></Icon>
<style>
:global(.qq19zibfc) {
  fill: currentColor;
  d: path("M4.23 13.5v-6h1v6zm14.54 3v-6h1v6zM6.807 20V4h10.384v16zm9.384-1V5H7.808v14zM12.588 8.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M7.808 5v14z");
}

</style>
