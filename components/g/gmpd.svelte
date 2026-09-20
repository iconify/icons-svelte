<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8s5js61e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:gmpd" {...props}></Icon>
<style>
:global(.r8s5js61e) {
  fill: var(--svg-color--ffb800, #ffb800);
  d: path("M21 7.615H7.343L3 9h6.655l-3.092 7.384H17.64l2.123-5.077h-6.406l-.582 1.385h4.833L16.638 15H8.724l2.51-6h9.185z");
}

</style>
