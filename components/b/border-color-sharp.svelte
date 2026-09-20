<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtyykm05v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:border-color-sharp" {...props}></Icon>
<style>
:global(.jtyykm05v) {
  fill: currentColor;
  d: path("M2 24v-2h20v2zm3-6.173v-2.5L16.952 3.381l2.488 2.505L7.5 17.828zM16.58 7.319l1.44-1.438l-1.074-1.073l-1.438 1.438z");
}

</style>
