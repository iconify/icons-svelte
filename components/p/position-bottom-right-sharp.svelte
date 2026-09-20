<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja1hrbbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:position-bottom-right-sharp" {...props}></Icon>
<style>
:global(.ja1hrbbqb) {
  fill: currentColor;
  d: path("M9 17h9v-3H9zm-6 4V3h18v18z");
}

</style>
