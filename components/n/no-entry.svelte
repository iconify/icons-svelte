<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="hoqgz_bdr"/><path class="gwjo6qa7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:no-entry" {...props}></Icon>
<style>
:global(.gwjo6qa7e) {
  d: path("M15.657 4.343a1 1 0 0 1 0 1.414l-9.9 9.9a1 1 0 0 1-1.414-1.414l9.9-9.9a1 1 0 0 1 1.414 0");
}

:global(.hoqgz_bdr) {
  d: path("M10 4a6 6 0 1 0 0 12a6 6 0 0 0 0-12m-8 6a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

</style>
