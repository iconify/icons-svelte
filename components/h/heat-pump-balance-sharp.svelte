<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lld_o-b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:heat-pump-balance-sharp" {...props}></Icon>
<style>
:global(.lld_o-b7o) {
  fill: currentColor;
  d: path("M4 6.6v12h6v-10h2v10h6v-11h2.175L19 8.75l1.4 1.425L24 6.6L20.4 3L19 4.425L20.175 5.6H16v11h-2v-10H8v10H6v-10zm-3 15v-10h22v10z");
}

</style>
