<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7hk-kbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hangout-video-outline" {...props}></Icon>
<style>
:global(.t7hk-kbrq) {
  fill: currentColor;
  d: path("M6 16h8v-3.2l4 3.2V8l-4 3.2V8H6zm-2 4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zM4 6v12z");
}

</style>
