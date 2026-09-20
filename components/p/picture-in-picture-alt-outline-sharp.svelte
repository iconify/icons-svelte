<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jshnfrb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-alt-outline-sharp" {...props}></Icon>
<style>
:global(.jshnfrb6g) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V6H4zm0 0V6zm7.308-1.038H19v-5.693h-7.692zm1-1v-3.693H18v3.692z");
}

</style>
