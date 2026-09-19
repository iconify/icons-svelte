<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="catwkmbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:opera-news" {...props}></Icon>
<style>
:global(.catwkmbuv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.605 9.576h-7.057c-4.203 0-5.999 1.063-7.017 5.078L4.5 38.424h10.29c1.194 0 1.914-.801 2.249-2.019zm-1.21 28.848h7.057c4.203 0 5.999-1.063 7.017-5.078L43.5 9.576H33.21c-1.194 0-1.914.801-2.249 2.019zm1.182-28.747L28.6 19.964m-5.237 18.46l-4.236-9.422");
}

</style>
