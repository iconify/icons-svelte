<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipj56slkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:amp-stories-sharp" {...props}></Icon>
<style>
:global(.ipj56slkj) {
  fill: currentColor;
  d: path("M8 19V5h8v14zm-3.385-2V7h1v10zm13.77 0V7h1v10z");
}

</style>
