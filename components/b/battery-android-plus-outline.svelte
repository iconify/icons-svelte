<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6vyv6b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-plus-outline" {...props}></Icon>
<style>
:global(.l6vyv6b4r) {
  fill: currentColor;
  d: path("M3 16V8zm1 2q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h12v2H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h12v2zm14-2v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
