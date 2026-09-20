<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzzqn_q6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:4g-mobiledata-badge-sharp" {...props}></Icon>
<style>
:global(.xzzqn_q6t) {
  fill: currentColor;
  d: path("M13 17h7v-6h-3.5v2H18v2h-3V9h5V7h-7zm-5 0h2v-3h2v-2h-2V7H8v5H6V7H4v7h4zm-7 4V3h22v18z");
}

</style>
