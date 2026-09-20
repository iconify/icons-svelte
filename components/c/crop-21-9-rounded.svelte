<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbxq03bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-21-9-rounded" {...props}></Icon>
<style>
:global(.cbxq03bye) {
  fill: currentColor;
  d: path("M4 17q-.825 0-1.412-.587T2 15V9q0-.825.588-1.412T4 7h16q.825 0 1.413.588T22 9v6q0 .825-.587 1.413T20 17z");
}

</style>
