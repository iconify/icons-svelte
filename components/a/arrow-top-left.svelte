<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3whdubey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-top-left" {...props}></Icon>
<style>
:global(.z3whdubey) {
  fill: currentColor;
  d: path("M17 19V9.5H6.921l3.793 3.792l-.708.714L5 9l5-5l.714.714L6.92 8.5H18V19z");
}

</style>
