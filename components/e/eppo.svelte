<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bh_94ab_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eppo" {...props}></Icon>
<style>
:global(.bh_94ab_q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.443 21.796q-1.635 2.454 0 4.909h2.728v5.454h2.181l2.182-4.909H25.08v3.273h3.818l1.636-3.273c17.455-.545 17.455-5.454 0-6l-1.636-3.273H25.08v3.273H12.534l-2.182-4.91H8.17v5.455z");
}

</style>
