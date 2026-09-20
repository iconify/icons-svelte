<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgm09us_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:gallery-thumbnail-sharp" {...props}></Icon>
<style>
:global(.pgm09us_e) {
  fill: currentColor;
  d: path("M1 19V5h14v14zm16-8V5h6v6zM4 15h8l-2.625-3.5L7.5 14l-1.375-1.825zm13 4v-6h6v6z");
}

</style>
