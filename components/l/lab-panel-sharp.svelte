<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxmne99pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:lab-panel-sharp" {...props}></Icon>
<style>
:global(.hxmne99pr) {
  fill: currentColor;
  d: path("M2 20v-7h2V8.321H3V5.04h7v3.28H9V13h6V8.321h-1V5.04h7v3.28h-1V13h2v7zm14-7h3V8.385h-3zM5 13h3V8.385H5z");
}

</style>
