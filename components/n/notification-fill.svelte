<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m3oyue7yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notification-fill" {...props}></Icon>
<style>
:global(.m3oyue7yv) {
  fill: currentColor;
  d: path("M216 128v80a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h80a8 8 0 0 1 0 16H48v152h152v-80a8 8 0 0 1 16 0M196 24a36 36 0 1 0 36 36a36 36 0 0 0-36-36");
}

</style>
