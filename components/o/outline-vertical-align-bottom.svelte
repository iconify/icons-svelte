<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nygylfb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-vertical-align-bottom" {...props}></Icon>
<style>
:global(.nygylfb8t) {
  fill: currentColor;
  d: path("M16 13h-3V3h-2v10H8l4 4zM4 19v2h16v-2z");
}

</style>
