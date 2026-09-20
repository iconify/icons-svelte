<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf62rgb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-landscape-outline" {...props}></Icon>
<style>
:global(.pf62rgb-f) {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v5h-2V6H4v12h11v2H4Zm13 0v-7h5v7h-5Zm-5-8Z");
}

</style>
