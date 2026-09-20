<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ghov41jrt"/><path class="lzak5bonm"/><path class="dn04bzn7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-right" {...props}></Icon>
<style>
:global(.dn04bzn7v) {
  d: path("M14 10a1 1 0 0 1-1 1H5a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1");
}

:global(.ghov41jrt) {
  d: path("M11.026 5.232a1 1 0 0 1 1.409.128l3.333 4a1 1 0 0 1-1.536 1.28l-3.334-4a1 1 0 0 1 .128-1.408");
}

:global(.lzak5bonm) {
  d: path("M11.026 14.768a1 1 0 0 1-.128-1.408l3.334-4a1 1 0 0 1 1.536 1.28l-3.333 4a1 1 0 0 1-1.409.128");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

</style>
