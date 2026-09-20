<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bczqfjbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:remove-from-queue-outline-sharp" {...props}></Icon>
<style>
:global(.bczqfjbkq) {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0 9v-2H2V3h20v16h-6v2zm-4-4h16V5H4zm0 0V5z");
}

</style>
