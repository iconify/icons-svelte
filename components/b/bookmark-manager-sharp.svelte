<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flfcdwbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bookmark-manager-sharp" {...props}></Icon>
<style>
:global(.flfcdwbmq) {
  fill: currentColor;
  d: path("M14.23 21v-2.21l5.96-5.934l2.19 2.204L16.44 21zm5.96-4.985l.925-.956l-.924-.943l-.95.95zM3 19V5h6.596l2 2H21v1.696l-9.154 9.096V19z");
}

</style>
