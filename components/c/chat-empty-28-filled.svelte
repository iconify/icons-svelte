<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="khq1n3wjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chat-empty-28-filled" {...props}></Icon>
<style>
:global(.khq1n3wjc) {
  fill: currentColor;
  d: path("M2 14C2 7.373 7.373 2 14 2s12 5.373 12 12s-5.373 12-12 12a11.95 11.95 0 0 1-5.637-1.404l-4.77 1.357a1.25 1.25 0 0 1-1.544-1.544l1.356-4.77A11.95 11.95 0 0 1 2 14");
}

</style>
