<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lqez1plih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-text-32-filled" {...props}></Icon>
<style>
:global(.lqez1plih) {
  fill: currentColor;
  d: path("M17 9V2H8a3 3 0 0 0-3 3v22a3 3 0 0 0 3 3h16a3 3 0 0 0 3-3V12h-7a3 3 0 0 1-3-3m-6 14h10a1 1 0 1 1 0 2H11a1 1 0 1 1 0-2m-1-3a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H11a1 1 0 0 1-1-1m1-5h10a1 1 0 1 1 0 2H11a1 1 0 1 1 0-2m8-6V2.117a3 3 0 0 1 1.293.762l5.828 5.828A3 3 0 0 1 26.883 10H20a1 1 0 0 1-1-1");
}

</style>
