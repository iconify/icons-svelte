<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_p1ylbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:ink-eraser-sharp" {...props}></Icon>
<style>
:global(.u_p1ylbcs) {
  fill: currentColor;
  d: path("M16.712 18h4.673v1H15.71zM4.558 19l-2.55-2.55L14.385 3.573l6.377 6.377l-8.8 9.05z");
}

</style>
