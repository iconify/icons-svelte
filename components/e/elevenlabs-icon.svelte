<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":416};
const content = `<path class="e0l8_jbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:elevenlabs-icon" {...props}></Icon>
<style>
:global(.e0l8_jbqo) {
  d: path("M170.667 0H256v415.289h-85.333zM0 0h85.333v415.289H0z");
}

</style>
