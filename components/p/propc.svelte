<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgdz79bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:propc" {...props}></Icon>
<style>
:global(.zgdz79bvi) {
  fill: var(--svg-color--febe05, #febe05);
  d: path("M3 3h11.893a6.107 6.107 0 0 1 0 12.214H8.786V8.786H3zm5.786 12.214V21H3v-5.786z");
}

</style>
