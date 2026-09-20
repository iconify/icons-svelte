<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btrf1pbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-plus-outline-sharp" {...props}></Icon>
<style>
:global(.btrf1pbfp) {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v8q-.525 0-1.025.088T15 12.35V6H9v14h2.35q.2.575.488 1.075t.687.925zm9 0v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
