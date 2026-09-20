<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blc490buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:health-cross-sharp" {...props}></Icon>
<style>
:global(.blc490buo) {
  fill: currentColor;
  d: path("M8.673 20v-4.673H4V8.692h4.673V4h6.635v4.692H20v6.635h-4.692V20z");
}

</style>
