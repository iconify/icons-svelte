<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="semdv364p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lte-mobiledata-outline-sharp" {...props}></Icon>
<style>
:global(.semdv364p) {
  fill: currentColor;
  d: path("M4 16V8h2v6h3v2zm7 0v-6H9V8h6v2h-2v6zm5 0V8h5v2h-3v1h3v2h-3v1h3v2z");
}

</style>
