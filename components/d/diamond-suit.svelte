<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="pz5q1vbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:diamond-suit" {...props}></Icon>
<style>
:global(.pz5q1vbos) {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M18.437 35.747c-.242.337-.632.337-.874 0L5.314 18.612c-.242-.338-.242-.886 0-1.224L17.563.253c.242-.338.632-.338.874 0l12.25 17.135c.241.338.241.886 0 1.224z");
}

</style>
