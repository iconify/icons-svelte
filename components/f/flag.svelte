<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxippw5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:flag" {...props}></Icon>
<style>
:global(.ohxippw5a) {
  fill: currentColor;
  d: path("M6 20.5V5h7.192l.4 2H19v8h-5.192l-.4-2H7v7.5z");
}

</style>
