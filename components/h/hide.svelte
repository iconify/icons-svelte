<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4-ikwbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:hide" {...props}></Icon>
<style>
:global(.t4-ikwbkj) {
  fill: currentColor;
  d: path("M4.714 19.98L4 19.268l5.1-5.094H6.058v-1h4.75v4.75h-1v-3.042zm8.478-9.191v-4.75h1V9.08l5.095-5.1l.713.713l-5.1 5.095h3.042v1z");
}

</style>
