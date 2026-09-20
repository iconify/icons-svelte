<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehdggtfkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:play-pass-sharp" {...props}></Icon>
<style>
:global(.ehdggtfkq) {
  fill: currentColor;
  d: path("M12 20q-.825 0-1.413.588T10 22H5V2h5q0 .825.588 1.413T12 4q.825 0 1.413-.588T14 2h5v20h-5q0-.825-.588-1.413T12 20Z");
}

</style>
