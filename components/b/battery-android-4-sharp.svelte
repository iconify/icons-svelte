<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj431tx8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-4-sharp" {...props}></Icon>
<style>
:global(.jj431tx8l) {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm11-2h6.5V8H12zm9.5-1.5v-5H23v5z");
}

</style>
