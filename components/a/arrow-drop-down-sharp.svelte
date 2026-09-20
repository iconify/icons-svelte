<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnz0zbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-drop-down-sharp" {...props}></Icon>
<style>
:global(.vbnz0zbzx) {
  fill: currentColor;
  d: path("M12 14.308L8.192 10.5h7.616z");
}

</style>
