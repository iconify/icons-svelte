<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py-2kccmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:display-add-sharp" {...props}></Icon>
<style>
:global(.py-2kccmu) {
  fill: currentColor;
  d: path("M18 9V6h-3V4h3V1h2v3h3v2h-3v3zM8 21v-2H2V3h11.35q-.175.475-.262.975T13 5q0 2.5 1.75 4.25T19 11q.825 0 1.588-.213T22 10.2V19h-6v2z");
}

</style>
