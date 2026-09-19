<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bc_idjjpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:replit" {...props}></Icon>
<style>
:global(.bc_idjjpz) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M7.75 15.5v-9a2 2 0 0 1 2-2H22a2 2 0 0 1 2 2v11H9.75a2 2 0 0 1-2-2Zm16.25 2h14.25a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H24zm-16.25 24v-9a2 2 0 0 1 2-2H24v11a2 2 0 0 1-2 2H9.75a2 2 0 0 1-2-2Z");
}

</style>
