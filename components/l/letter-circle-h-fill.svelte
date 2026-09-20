<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q25qazuop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:letter-circle-h-fill" {...props}></Icon>
<style>
:global(.q25qazuop) {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m40 144a8 8 0 0 1-16 0v-32h-48v32a8 8 0 0 1-16 0V88a8 8 0 0 1 16 0v32h48V88a8 8 0 0 1 16 0Z");
}

</style>
