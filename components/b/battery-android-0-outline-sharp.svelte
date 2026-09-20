<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcm_t-mxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-0-outline-sharp" {...props}></Icon>
<style>
:global(.rcm_t-mxw) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm1-1h15.885V8H3zm17.885-1.884V9.904H22v4.212zM3 16V8z");
}

</style>
