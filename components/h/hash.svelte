<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rd4w2eb7i"/><path class="q3434gboo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:hash" {...props}></Icon>
<style>
:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.q3434gboo) {
  d: path("M7.833 3.004a1 1 0 0 1 .914 1.08l-1 12a1 1 0 1 1-1.994-.167l1-12a1 1 0 0 1 1.08-.913m5.5 0a1 1 0 0 1 .914 1.08l-1 12a1 1 0 0 1-1.993-.167l1-12a1 1 0 0 1 1.08-.913");
}

:global(.rd4w2eb7i) {
  d: path("M3 7.25a1 1 0 0 1 1-1h12a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m0 5.5a1 1 0 0 1 1-1h12a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1");
}

</style>
