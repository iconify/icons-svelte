<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxtbp199i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:info-i" {...props}></Icon>
<style>
:global(.pxtbp199i) {
  fill: currentColor;
  d: path("M10.588 6.413Q10 5.825 10 5t.588-1.412T12 3t1.413.588T14 5t-.587 1.413T12 7t-1.412-.587M10.5 21V9h3v12z");
}

</style>
