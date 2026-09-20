<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8b-28qxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:man-outline-sharp" {...props}></Icon>
<style>
:global(.t8b-28qxw) {
  fill: currentColor;
  d: path("M10 22v-7H8V7h8v8h-2v7zm2-16q-.825 0-1.412-.587T10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6");
}

</style>
