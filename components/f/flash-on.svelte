<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtw2t2byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flash-on" {...props}></Icon>
<style>
:global(.wtw2t2byk) {
  fill: currentColor;
  d: path("M10 22v-8H7V2h10l-2 7h4z");
}

</style>
