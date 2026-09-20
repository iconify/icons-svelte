<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l0eigkb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notebook-fill" {...props}></Icon>
<style>
:global(.l0eigkb6x) {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M80 208H48V48h32Zm96-56h-64a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16m0-32h-64a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16");
}

</style>
