<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgwli83vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:general-device-outline" {...props}></Icon>
<style>
:global(.tgwli83vs) {
  fill: currentColor;
  d: path("M8 18V5q0-.825.588-1.412T10 3h4q.825 0 1.413.588T16 5v13zm2-2h4V5h-4zm-2 5v-2h8v2zm2-5h4z");
}

</style>
