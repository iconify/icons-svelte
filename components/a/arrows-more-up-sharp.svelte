<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_m69bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrows-more-up-sharp" {...props}></Icon>
<style>
:global(.ft_m69bqd) {
  fill: currentColor;
  d: path("M12 19v-9H3V8h11v11zm5-5V5H8V3h11v11z");
}

</style>
