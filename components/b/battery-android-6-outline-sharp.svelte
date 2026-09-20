<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n97e2fn-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-6-outline-sharp" {...props}></Icon>
<style>
:global(.n97e2fn-c) {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm14-1h2.885V8H16zm4.885-1.884V9.904H22v4.212z");
}

</style>
