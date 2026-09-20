<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr1b-bb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-frame-5-outline-sharp" {...props}></Icon>
<style>
:global(.sr1b-bb9q) {
  fill: currentColor;
  d: path("M4.385 14.616V9.385h9v5.23zM2 17V7h17.885v10zm1-1h15.885V8H3zm17.885-1.884V9.904H22v4.212z");
}

</style>
