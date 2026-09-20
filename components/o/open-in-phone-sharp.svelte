<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epqz-fb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:open-in-phone-sharp" {...props}></Icon>
<style>
:global(.epqz-fb8m) {
  fill: currentColor;
  d: path("M5 23v-8h2v3h10V6H7v3H5V1h14v22zm5-7l-1.4-1.4l1.55-1.6H2v-2h8.15L8.6 9.4L10 8l4 4z");
}

</style>
