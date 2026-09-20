<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awvu8k_zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mint" {...props}></Icon>
<style>
:global(.awvu8k_zt) {
  fill: var(--svg-color--30bf54, #30bf54);
  d: path("M3 3a9 9 0 0 1 9 9a9 9 0 0 1-9-9m18 18a9 9 0 0 1-9-9a9 9 0 0 1 9 9m-9-9a4.5 4.5 0 0 1 4.5-4.5A4.5 4.5 0 0 1 12 12m0 0a4.5 4.5 0 0 1-4.5 4.5A4.5 4.5 0 0 1 12 12");
}

</style>
