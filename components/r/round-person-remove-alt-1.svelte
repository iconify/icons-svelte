<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbmh2sb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-person-remove-alt-1" {...props}></Icon>
<style>
:global(.jbmh2sb7c) {
  fill: currentColor;
  d: path("M14 8c0-2.21-1.79-4-4-4S6 5.79 6 8s1.79 4 4 4s4-1.79 4-4M2 18v1c0 .55.45 1 1 1h14c.55 0 1-.45 1-1v-1c0-2.66-5.33-4-8-4s-8 1.34-8 4m16-8h4c.55 0 1 .45 1 1s-.45 1-1 1h-4c-.55 0-1-.45-1-1s.45-1 1-1");
}

</style>
