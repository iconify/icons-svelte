<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="eubhabc9r"/><path class="suklrfbex"/><path class="uz9kyex_q"/><path class="atz7vnbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-syria" {...props}></Icon>
<style>
:global(.atz7vnbub) {
  d: path("M9.177 18.332l-.633 1.947l1.656-1.203l1.656 1.203l-.633-1.947l1.656-1.202h-2.047l-.632-1.947l-.632 1.947H7.521zm15.6 0l-.633 1.947l1.656-1.203l1.656 1.203l-.633-1.947l1.656-1.202h-2.047l-.632-1.947l-.632 1.947h-2.047z");
  fill: var(--svg-color--007a3d, #007A3D);
}

:global(.eubhabc9r) {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 13h36v10H0z");
}

:global(.suklrfbex) {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4z");
}

:global(.uz9kyex_q) {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 31H4a4 4 0 0 1-4-4v-4h36v4a4 4 0 0 1-4 4z");
}

</style>
