<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvtcp1b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:desk-outline-sharp" {...props}></Icon>
<style>
:global(.dvtcp1b1f) {
  fill: currentColor;
  d: path("M2 18V6h20v12h-2v-2h-4v2h-2V8H4v10zm14-8h4V8h-4zm0 4h4v-2h-4z");
}

</style>
