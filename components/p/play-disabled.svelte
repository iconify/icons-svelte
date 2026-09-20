<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmcnvjbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:play-disabled" {...props}></Icon>
<style>
:global(.tmcnvjbeo) {
  fill: currentColor;
  d: path("M16.45 13.6L8 5.15V5l11 7zm3.3 9L13 15.8L8 19v-8.2L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>
