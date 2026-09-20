<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyem7cb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:cases-sharp" {...props}></Icon>
<style>
:global(.jyem7cb1f) {
  fill: currentColor;
  d: path("M1 22V9h2v11h17v2zm4-4V5h5V1h8v4h5v13zm7-13h4V3h-4z");
}

</style>
