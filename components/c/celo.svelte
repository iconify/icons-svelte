<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k53vtabkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:celo" {...props}></Icon>
<style>
:global(.k53vtabkp) {
  fill: var(--svg-color--fcfe52, #fcfe52);
  d: path("M3 3h18v6.429h-3.111a6.428 6.428 0 1 0 0 5.143H21V21H3z");
}

</style>
