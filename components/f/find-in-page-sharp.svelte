<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spgdpybjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:find-in-page-sharp" {...props}></Icon>
<style>
:global(.spgdpybjo) {
  fill: currentColor;
  d: path("M4 22V2h11l5 6v11.65L15.45 15q.275-.425.413-.925T16 13q0-1.65-1.175-2.825T12 9t-2.825 1.175T8 13t1.175 2.825T12 17q.575 0 1.075-.137T14 16.45L19.6 22zm6.588-7.587Q10 13.825 10 13t.588-1.412T12 11t1.413.588T14 13t-.587 1.413T12 15t-1.412-.587");
}

</style>
