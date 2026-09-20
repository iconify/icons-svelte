<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl9tq28ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:priority-high-sharp" {...props}></Icon>
<style>
:global(.xl9tq28ic) {
  fill: currentColor;
  d: path("M12 21q-.825 0-1.412-.587T10 19t.588-1.412T12 17t1.413.588T14 19t-.587 1.413T12 21m-2-6V3h4v12z");
}

</style>
