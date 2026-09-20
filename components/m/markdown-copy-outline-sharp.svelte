<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyvliobvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:markdown-copy-outline-sharp" {...props}></Icon>
<style>
:global(.cyvliobvq) {
  fill: currentColor;
  d: path("M7.5 17V3h11v14zm1-1h9V4h-9zm-4 4V6.616h1V19h9.385v1zm5.558-7.308h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V7.308h-5.884zM8.5 16V4z");
}

</style>
