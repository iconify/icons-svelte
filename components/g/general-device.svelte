<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrrftb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:general-device" {...props}></Icon>
<style>
:global(.vlrrftb5p) {
  fill: currentColor;
  d: path("M8 18V5q0-.825.588-1.412T10 3h4q.825 0 1.413.588T16 5v13zm0 3v-2h8v2z");
}

</style>
