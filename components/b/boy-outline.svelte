<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph37z3bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:boy-outline" {...props}></Icon>
<style>
:global(.ph37z3bzk) {
  fill: currentColor;
  d: path("M10.763 6.988q-.513-.513-.513-1.238t.513-1.237T12 4t1.238.513t.512 1.237t-.513 1.238T12 7.5t-1.237-.513M10 20v-5H9v-4.5q0-.825.588-1.412T11 8.5h2q.825 0 1.413.588T15 10.5V15h-1v5z");
}

</style>
