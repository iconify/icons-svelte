<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm74k-cqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-close-fill-sharp" {...props}></Icon>
<style>
:global(.tm74k-cqp) {
  fill: currentColor;
  d: path("m17.707 17.707l-5 5a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0l10 10a1 1 0 0 1 0 1.414Zm-7-8.414a.999.999 0 1 0-1.414 1.414L10.586 12l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 13.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 12l1.293-1.293a.999.999 0 1 0-1.414-1.414L12 10.586Z");
}

</style>
