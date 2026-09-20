<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seek8sbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:man-2-sharp" {...props}></Icon>
<style>
:global(.seek8sbjc) {
  fill: currentColor;
  d: path("M10.5 22v-7H8V7h8v8h-2.5v7zM12 6q-.825 0-1.412-.587T10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6");
}

</style>
