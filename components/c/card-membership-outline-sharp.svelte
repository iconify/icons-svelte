<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8_9kccng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:card-membership-outline-sharp" {...props}></Icon>
<style>
:global(.e8_9kccng) {
  fill: currentColor;
  d: path("M4 15h16v-2H4zm4 7v-5H2V2h20v15h-6v5l-4-2zM4 10h16V4H4zm0 5V4z");
}

</style>
