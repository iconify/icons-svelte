<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8tv1my1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-camera-rear-sharp" {...props}></Icon>
<style>
:global(.o8tv1my1c) {
  fill: currentColor;
  d: path("m9.85 22.5l-1.4-1.4l1.1-1.1H5v-2h4.55l-1.1-1.1l1.4-1.4l3.5 3.5zM14 20v-2h5v2zM11.288 5.288Q11 5.575 11 6t.288.713T12 7t.713-.288T13 6t-.288-.712T12 5t-.712.288M5 17V2h14v5.1h1v4.8h-1V17h-6.225L9.85 14.075L6.925 17z");
}

</style>
