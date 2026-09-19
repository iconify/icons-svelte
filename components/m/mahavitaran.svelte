<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9wczhbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mahavitaran" {...props}></Icon>
<style>
:global(.r9wczhbpg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 14.665l-8.511 9.846l3.759.898l-7.068 7.926H4.5l7.435-7.64l-3.677-.612zm0 0l8.511 9.846l-3.759.898l7.068 7.926h7.68l-7.435-7.64l3.677-.612z");
}

</style>
