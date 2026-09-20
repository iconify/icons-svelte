<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clo0pwgdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hov-outline-sharp" {...props}></Icon>
<style>
:global(.clo0pwgdq) {
  fill: currentColor;
  d: path("M12 22L6 12l6-10l6 10zm0-3.9l3.675-6.1L12 5.9L8.325 12zm0-6.1");
}

</style>
