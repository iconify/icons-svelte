<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynxbl1b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-full-sharp" {...props}></Icon>
<style>
:global(.ynxbl1b6d) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm18.885-2.884V9.904H22v4.212z");
}

</style>
