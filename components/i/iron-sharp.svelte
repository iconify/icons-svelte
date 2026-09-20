<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq7hykbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:iron-sharp" {...props}></Icon>
<style>
:global(.mq7hykbbb) {
  fill: currentColor;
  d: path("M3 17v-2.077q0-1.364.992-2.336t2.412-.971h8.962V9H9.269v1.5h-1V8h8.097v6.462H18V7h3v1h-2v7.462h-2.634V17z");
}

</style>
