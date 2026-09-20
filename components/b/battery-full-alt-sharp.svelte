<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcem6-bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-full-alt-sharp" {...props}></Icon>
<style>
:global(.jcem6-bqg) {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10z");
}

</style>
