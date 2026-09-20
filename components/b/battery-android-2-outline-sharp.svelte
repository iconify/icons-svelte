<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl66eajx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-2-outline-sharp" {...props}></Icon>
<style>
:global(.gvl66eajx) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm6-1h10.885V8H8zm12.885-1.884V9.904H22v4.212z");
}

</style>
