<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3pwhbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-android-plus-sharp" {...props}></Icon>
<style>
:global(.hy3pwhbph) {
  fill: currentColor;
  d: path("M2 17V7h14.116v2.116h-3v5.769h3V17zm16.5-1.5v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
