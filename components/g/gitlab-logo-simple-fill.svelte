<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pkrpqfdaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:gitlab-logo-simple-fill" {...props}></Icon>
<style>
:global(.pkrpqfdaq) {
  fill: currentColor;
  d: path("m208.14 178.06l-73.27 51.76a11.91 11.91 0 0 1-13.74 0l-73.27-51.76a57.19 57.19 0 0 1-22-61L45.75 41a11.94 11.94 0 0 1 22.79-1.11L86.22 88h83.56l17.68-48.13A11.94 11.94 0 0 1 210.25 41l19.9 76.12a57.19 57.19 0 0 1-22.01 60.94");
}

</style>
