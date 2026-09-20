<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo4w__bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:nest-multi-room-sharp" {...props}></Icon>
<style>
:global(.bo4w__bep) {
  fill: currentColor;
  d: path("m5 9.5l7-5.27l7 5.27zM5 20v-4.25h8.5V20zm9.5 0v-4.25H19V20zM5 14.75V10.5h4.5v4.25zm5.5 0V10.5H19v4.25z");
}

</style>
