<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugbvcidre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-down-left-fill-sharp" {...props}></Icon>
<style>
:global(.ugbvcidre) {
  fill: currentColor;
  d: path("M18 16a1 1 0 0 1-1 1H9.414l3.293 3.293a.999.999 0 1 1-1.414 1.414l-5-5a1 1 0 0 1 0-1.414l5-5a.999.999 0 1 1 1.414 1.414L9.414 15H16V3a1 1 0 0 1 2 0Z");
}

</style>
