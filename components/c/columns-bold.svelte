<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m65j_bc8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:columns-bold" {...props}></Icon>
<style>
:global(.m65j_bc8e) {
  fill: currentColor;
  d: path("M100 28H64a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h36a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H68V52h28Zm96-176h-36a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h36a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176h-28V52h28Z");
}

</style>
