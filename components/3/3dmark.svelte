<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bzqabs8wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:3dmark" {...props}></Icon>
<style>
:global(.bzqabs8wk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.842 5.5l29.375 24.707l-14.712-3.739zm28.593 26.296L6.783 26.615l20.577 9.238zm.171 1.784L19.858 42.5l12.292-.806z");
}

</style>
