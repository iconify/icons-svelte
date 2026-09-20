<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y80307bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:calendar-view-week-outline-sharp" {...props}></Icon>
<style>
:global(.y80307bbw) {
  fill: currentColor;
  d: path("M12.5 18h3.25V6H12.5zm-4.25 0h3.25V6H8.25zM4 18h3.25V6H4zm12.75 0H20V6h-3.25zM3 19V5h18v14z");
}

</style>
