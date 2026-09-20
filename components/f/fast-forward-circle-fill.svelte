<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="llkzm1bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:fast-forward-circle-fill" {...props}></Icon>
<style>
:global(.llkzm1bws) {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m68.8 110.4l-48 36a8 8 0 0 1-4.8 1.6a8 8 0 0 1-8-8v-36a8 8 0 0 1-3.2 6.4l-48 36A8 8 0 0 1 80 172a8 8 0 0 1-8-8V92a8 8 0 0 1 12.8-6.4l48 36a8 8 0 0 1 3.2 6.4V92a8 8 0 0 1 12.8-6.4l48 36a8 8 0 0 1 0 12.8");
}

</style>
