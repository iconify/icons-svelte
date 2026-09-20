<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dsnimea2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-pattern-32-light" {...props}></Icon>
<style>
:global(.dsnimea2o) {
  fill: currentColor;
  d: path("M29 24.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5zM24.5 4h-17A3.5 3.5 0 0 0 4 7.5V10h24V7.5A3.5 3.5 0 0 0 24.5 4M4 16.293L9.293 11H4zm0 1.414V20h3.293l9-9h-5.586zM17.707 11l-9 9h5.586l9-9zm7 0l-9 9h5.586L28 13.293V11zM28 14.707L22.707 20H28z");
}

</style>
