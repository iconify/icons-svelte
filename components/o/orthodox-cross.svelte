<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gcukz1agq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:orthodox-cross" {...props}></Icon>
<style>
:global(.gcukz1agq) {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M55 32v-8H36v-7h6V9h-6V2h-8v7h-6v8h6v7H9v8h19v13l-7-3v8l7 3v9h8v-6l7 3v-8l-7-3V32z");
}

</style>
