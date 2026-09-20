<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4i1wztjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:cases-outline-sharp" {...props}></Icon>
<style>
:global(.l4i1wztjw) {
  fill: currentColor;
  d: path("M2 20.192V9.423h1v9.77h15.5v1zm3-3v-11h5.308V3h6.384v3.192H22v11zm6.308-11h4.384V4h-4.384zM6 16.192h15v-9H6zm0-9v9z");
}

</style>
