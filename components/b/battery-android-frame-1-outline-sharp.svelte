<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahvn-hknu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-frame-1-outline-sharp" {...props}></Icon>
<style>
:global(.ahvn-hknu) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm1-1h15.885V8H3zm17.885-1.884V9.904H22v4.212zm-16.5.5V9.385h1v5.23z");
}

</style>
