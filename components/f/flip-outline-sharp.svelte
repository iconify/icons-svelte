<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="indgsqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flip-outline-sharp" {...props}></Icon>
<style>
:global(.indgsqbax) {
  fill: currentColor;
  d: path("M15 5V3h2v2zm0 16v-2h2v2zm4-16V3h2v2zm0 16v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zM9 21H3V3h6v2H5v14h4zm2 2V1h2v22z");
}

</style>
