<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zlpn6ebcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:motioneasetune" {...props}></Icon>
<style>
:global(.zlpn6ebcc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.076 20.528v6.944m-7.53-14.559V35.39M23.966 5.5v37m-7.411-29.587V35.39M8.924 20.528v6.944");
}

</style>
