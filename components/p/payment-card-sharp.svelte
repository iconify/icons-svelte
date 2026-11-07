<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbbue8b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:payment-card-sharp" {...props}></Icon>
<style>
:global(.sbbue8b2n) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h10L10 7H5zm8-8h6V7h-6z");
}

</style>
