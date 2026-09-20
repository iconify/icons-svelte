<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byw4e3b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-down-right-24-regular" {...props}></Icon>
<style>
:global(.byw4e3b6b) {
  fill: currentColor;
  d: path("m16.5 7.811l-8.689 8.69h8.44a.25.25 0 0 0 .25-.25zm-.633-1.487c.787-.788 2.133-.23 2.133.884v9.042A1.75 1.75 0 0 1 16.25 18H7.208c-1.114 0-1.672-1.346-.884-2.133z");
}

</style>
