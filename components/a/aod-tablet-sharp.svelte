<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a60dc9bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:aod-tablet-sharp" {...props}></Icon>
<style>
:global(.a60dc9bnn) {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6zm2-6.5V10h8v1.5zm1 3V13h6v1.5z");
}

</style>
