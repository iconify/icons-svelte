<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njj0_t8pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-3-sharp" {...props}></Icon>
<style>
:global(.njj0_t8pt) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm8-1h8.885V8H10zm10.885-1.884V9.904H22v4.212z");
}

</style>
