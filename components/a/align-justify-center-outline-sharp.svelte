<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwcoexbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-justify-center-outline-sharp" {...props}></Icon>
<style>
:global(.dwcoexbss) {
  fill: currentColor;
  d: path("M11 22V2h2v20zm4-5V7h3v10zm-9 0V7h3v10z");
}

</style>
