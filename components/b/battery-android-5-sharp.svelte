<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcl4nbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-5-sharp" {...props}></Icon>
<style>
:global(.hgcl4nbkr) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm12-1h4.885V8H14zm6.885-1.884V9.904H22v4.212z");
}

</style>
