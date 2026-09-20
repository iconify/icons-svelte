<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwabcdchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:payment-card-outline-sharp" {...props}></Icon>
<style>
:global(.zwabcdchs) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm1-1h10L10 7H5zm8-8h6V7h-6zm-9 9V6z");
}

</style>
