<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="cw9lh_m5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-bidirectional-up-down-28-regular" {...props}></Icon>
<style>
:global(.cw9lh_m5a) {
  fill: currentColor;
  d: path("M13.75 3c.199 0 .39.08.53.22l6 6a.75.75 0 1 1-1.06 1.06L14.5 5.56v16.88l4.72-4.72a.75.75 0 0 1 1.06 1.06l-6 6a.75.75 0 0 1-1.06 0l-6-6a.75.75 0 1 1 1.06-1.06L13 22.44V5.56l-4.72 4.72a.75.75 0 0 1-1.06-1.06l6-6a.75.75 0 0 1 .53-.22");
}

</style>
