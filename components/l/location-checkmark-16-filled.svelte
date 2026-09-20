<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u31ja0rgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:location-checkmark-16-filled" {...props}></Icon>
<style>
:global(.u31ja0rgh) {
  fill: currentColor;
  d: path("M14 7c0 2.876-3.1 6.01-4.844 7.544a1.736 1.736 0 0 1-2.312 0C5.101 13.01 2 9.876 2 7a6 6 0 1 1 12 0m-3.88-1.836L7.25 8.042L5.854 6.646l-.07-.058a.5.5 0 0 0-.638.765l1.75 1.75l.07.058a.5.5 0 0 0 .638-.058l3.224-3.233l.058-.07a.5.5 0 0 0-.766-.636");
}

</style>
