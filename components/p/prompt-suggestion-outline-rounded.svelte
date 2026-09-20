<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lini54bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:prompt-suggestion-outline-rounded" {...props}></Icon>
<style>
:global(.lini54bwt) {
  fill: currentColor;
  d: path("M18.079 13.539H7.827q-1.586 0-2.707-1.092Q4 11.356 4 9.769t1.12-2.678T7.827 6q.214 0 .357.143t.143.357t-.143.357T7.827 7q-1.165 0-1.996.802T5 9.769t.83 1.967t1.997.802h10.252L14.589 9.1q-.16-.14-.163-.351t.163-.357q.14-.14.344-.14t.344.14l4.139 4.062q.242.242.242.575t-.243.575l-4.138 4.062q-.146.146-.344.143t-.344-.15q-.16-.145-.163-.353t.163-.354z");
}

</style>
