<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvk01sb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:exit-to-app-sharp" {...props}></Icon>
<style>
:global(.hvk01sb6m) {
  fill: currentColor;
  d: path("M4 20v-4.73h1V19h14V5H5v3.73H4V4h16v16zm6.846-4.077l-.707-.72l2.703-2.703H4v-1h8.842L10.14 8.796l.707-.719L14.77 12z");
}

</style>
