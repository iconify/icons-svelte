<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ng2939b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:minus" {...props}></Icon>
<style>
:global(.ng2939b1r) {
  fill: currentColor;
  d: path("M5 11a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

</style>
