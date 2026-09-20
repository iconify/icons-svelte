<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2n62rbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:aod-tablet-rounded" {...props}></Icon>
<style>
:global(.d2n62rbyb) {
  fill: currentColor;
  d: path("M3 20q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20zm3-2h12V6H6zm2.75-6.5q-.325 0-.537-.213T8 10.75t.213-.537T8.75 10h6.5q.325 0 .538.213t.212.537t-.213.538t-.537.212zm1 3q-.325 0-.537-.213T9 13.75t.213-.537T9.75 13h4.5q.325 0 .538.213t.212.537t-.213.538t-.537.212z");
}

</style>
