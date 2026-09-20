<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbmwctb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-3-sharp" {...props}></Icon>
<style>
:global(.mbmwctb9y) {
  fill: currentColor;
  d: path("M9 20h6v-2H9zm-4 3V1h14v5.1h1v4.8h-1V23z");
}

</style>
