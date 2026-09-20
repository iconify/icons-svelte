<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ble96u4kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:playing-cards-sharp" {...props}></Icon>
<style>
:global(.ble96u4kc) {
  fill: currentColor;
  d: path("m15.2 14.8l1.15-4.15L12.8 8.2l-1.15 4.15zM4 18.825l-2.65-1.25L4 11.85zM6 21v-8l2.9 8zm5.25.575L5.425 5.55L16.75 1.425l5.825 16.025z");
}

</style>
