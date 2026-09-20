<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mamjj4b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:cleaning-sharp" {...props}></Icon>
<style>
:global(.mamjj4b7a) {
  fill: currentColor;
  d: path("m9 7l1-2V4H9V2h7v2l-1 2h-3V5l-2 2zM8 22v-7.425L12 7h4v15z");
}

</style>
