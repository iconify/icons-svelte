<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7x6fjnug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-3-outline-sharp" {...props}></Icon>
<style>
:global(.p7x6fjnug) {
  fill: currentColor;
  d: path("M1 18V6h19.5v12zm9-2h8.5V8H10zm11.5-1.5v-5H23v5z");
}

</style>
