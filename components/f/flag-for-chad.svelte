<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="xuph2qbqs"/><path class="yc4aorh9m"/><path class="tkqt_0b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-chad" {...props}></Icon>
<style>
:global(.tkqt_0b0n) {
  fill: var(--svg-color--c60c30, #c60c30);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.xuph2qbqs) {
  fill: var(--svg-color--002664, #002664);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.yc4aorh9m) {
  fill: var(--svg-color--fecb00, #fecb00);
  d: path("M12 5h12v26H12z");
}

</style>
