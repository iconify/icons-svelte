<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p85svyawr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:expand-content-outline-sharp" {...props}></Icon>
<style>
:global(.p85svyawr) {
  fill: currentColor;
  d: path("M5 19v-6h2v4h4v2zm12-8V7h-4V5h6v6z");
}

</style>
