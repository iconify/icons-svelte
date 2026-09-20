<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmww7ihsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-menu-open" {...props}></Icon>
<style>
:global(.dmww7ihsb) {
  fill: currentColor;
  d: path("M10 20V4h1v16zm3.385-4.365v-7.25L16.865 12z");
}

</style>
