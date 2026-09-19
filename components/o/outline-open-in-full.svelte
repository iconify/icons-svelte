<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvt2f9bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-open-in-full" {...props}></Icon>
<style>
:global(.jvt2f9bfe) {
  fill: currentColor;
  d: path("M21 11V3h-8l3.29 3.29l-10 10L3 13v8h8l-3.29-3.29l10-10z");
}

</style>
