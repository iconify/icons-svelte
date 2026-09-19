<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kccta8fqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:event-seat" {...props}></Icon>
<style>
:global(.kccta8fqp) {
  fill: currentColor;
  d: path("M4 18v3h3v-3h10v3h3v-6H4zm15-8h3v3h-3zM2 10h3v3H2zm15 3H7V5c0-1.1.9-2 2-2h6c1.1 0 2 .9 2 2z");
}

</style>
