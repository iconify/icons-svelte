<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dai24z1ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-0-bulk-round" {...props}></Icon>
<style>
:global(.dai24z1ii) {
  fill: currentColor;
  d: path("M9 7v10a3 3 0 1 0 6 0V7a3 3 0 1 0-6 0M7 17V7a5 5 0 0 1 10 0v10a5 5 0 0 1-10 0");
}

</style>
