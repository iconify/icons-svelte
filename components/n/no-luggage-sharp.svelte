<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feknm5bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:no-luggage-sharp" {...props}></Icon>
<style>
:global(.feknm5bxq) {
  fill: currentColor;
  d: path("M7 22v-1H5V7.825L.675 3.5L2.1 2.075l19.8 19.8l-1.425 1.425l-2.525-2.525V21H17v1h-2v-1H9v1zm2-4h2v-4.175l-2-2zm4 0h2v-.175l-2-2zm6-1.875l-4-4V9h-2v1.125l-4-4V2h6v4h4zM11 6h2V4h-2z");
}

</style>
