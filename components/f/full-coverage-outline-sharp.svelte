<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gouislc6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:full-coverage-outline-sharp" {...props}></Icon>
<style>
:global(.gouislc6l) {
  fill: currentColor;
  d: path("M3 20V8h1v11h14v1zm4-4V4h15v12zm1-1h13V5H8zm2-3h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4zm-7 6V5z");
}

</style>
