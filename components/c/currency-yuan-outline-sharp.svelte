<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qabykrbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:currency-yuan-outline-sharp" {...props}></Icon>
<style>
:global(.qabykrbxw) {
  fill: currentColor;
  d: path("M11.5 20v-6.5h-5v-1h4.802L5.904 4h1.202L12 11.742L16.894 4h1.202l-5.398 8.5H17.5v1h-5V20z");
}

</style>
