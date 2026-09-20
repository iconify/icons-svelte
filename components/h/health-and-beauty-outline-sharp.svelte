<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raz8wcc1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:health-and-beauty-outline-sharp" {...props}></Icon>
<style>
:global(.raz8wcc1v) {
  fill: currentColor;
  d: path("M5 22L1 11l5-3V2h4v6l5 3l-4 11zm11 0v-2h4v-2h-4v-2h4v-2h-4v-2h4v-2h-4V8h4V6h-4V4h7v18zm-9.6-2h3.2l2.95-8.15L9.45 10h-2.9l-3.1 1.85zM8 15");
}

</style>
