<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5ylerb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:health-cross-rounded" {...props}></Icon>
<style>
:global(.q5ylerb7f) {
  fill: currentColor;
  d: path("M9 21q-.425 0-.712-.288T8 20v-4H4q-.425 0-.712-.288T3 15V9q0-.425.288-.712T4 8h4V4q0-.425.288-.712T9 3h6q.425 0 .713.288T16 4v4h4q.425 0 .713.288T21 9v6q0 .425-.288.713T20 16h-4v4q0 .425-.288.713T15 21z");
}

</style>
