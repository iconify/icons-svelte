<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ady_bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-start-square" {...props}></Icon>
<style>
:global(.d5ady_bcq) {
  fill: currentColor;
  d: path("M11.423 15.923H3.577V8.077h7.846V11.5h9.5v1h-9.5z");
}

</style>
