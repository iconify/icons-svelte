<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm-2b3ofr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:resume-rounded" {...props}></Icon>
<style>
:global(.qm-2b3ofr) {
  fill: currentColor;
  d: path("M6 17V7q0-.425.288-.712T7 6t.713.288T8 7v10q0 .425-.288.713T7 18t-.712-.288T6 17m5.525.1q-.5.3-1.012 0T10 16.225v-8.45q0-.575.513-.875t1.012 0l7.05 4.25q.5.3.5.85t-.5.85z");
}

</style>
