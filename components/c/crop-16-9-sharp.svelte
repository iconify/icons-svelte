<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oilaccbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-16-9-sharp" {...props}></Icon>
<style>
:global(.oilaccbua) {
  fill: currentColor;
  d: path("M4 16V8h16v8z");
}

</style>
