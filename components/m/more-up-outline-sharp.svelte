<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsc8gb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:more-up-outline-sharp" {...props}></Icon>
<style>
:global(.ixsc8gb_e) {
  fill: currentColor;
  d: path("M17 16V7H8V5h11v11zm-5 5v-9H3v-2h11v11z");
}

</style>
