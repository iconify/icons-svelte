<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q3m8phb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naver-game-streaming" {...props}></Icon>
<style>
:global(.q3m8phb7e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.2 5.5h13.71l-3.432 5.386H42.5L26.744 32.407h13.7V42.5H5.5l16.444-22.2h-13.7z");
}

</style>
