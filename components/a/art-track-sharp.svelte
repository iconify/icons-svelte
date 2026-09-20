<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0n4bqbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:art-track-sharp" {...props}></Icon>
<style>
:global(.b0n4bqbxz) {
  fill: currentColor;
  d: path("M15 19H1V5h14zm2 0V5h2v14zm4 0V5h2v14zM4 15h8l-2.6-3.5L7.5 14l-1.4-1.85z");
}

</style>
