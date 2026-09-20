<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yai0f0baj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:block-24-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.yai0f0baj) {
  d: path("M12 2.001c5.524 0 10 4.477 10 10s-4.476 10-10 10c-5.522 0-10-4.477-10-10s4.478-10 10-10zm4.25 9.25h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
  fill: currentColor;
}

</style>
