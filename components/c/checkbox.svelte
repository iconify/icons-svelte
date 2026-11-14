<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws-oeibkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:checkbox" {...props}></Icon>
<style>
:global(.ws-oeibkb) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.375 3.25h7.25q2.123 0 3.624 1.501t1.501 3.624v7.25q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 15.625v-7.25q0-2.123 1.501-3.624T8.375 3.25");
}

</style>
