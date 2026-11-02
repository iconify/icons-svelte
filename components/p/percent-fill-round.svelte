<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdffsaciv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:percent-fill-round" {...props}></Icon>
<style>
:global(.sdffsaciv) {
  fill: currentColor;
  d: path("m19.707 5.707l-14 14a.999.999 0 1 1-1.414-1.414l14-14a.999.999 0 1 1 1.414 1.414M4 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
