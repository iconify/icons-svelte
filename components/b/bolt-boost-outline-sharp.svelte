<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8sp8nbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bolt-boost-outline-sharp" {...props}></Icon>
<style>
:global(.y8sp8nbxd) {
  fill: currentColor;
  d: path("m13.52 20l.942-6.539H8.994L15.846 4h.423l-.942 6.558h5.448L13.942 20zM4 17.25v-1h7.72l-.147 1zM3 12.5v-1h4.489l-.739 1zm1.98-4.75v-1h6.024l-.72 1z");
}

</style>
