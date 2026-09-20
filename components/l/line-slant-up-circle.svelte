<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pgo0c5f-d"/><path class="hdxpysbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:line-slant-up-circle" {...props}></Icon>
<style>
:global(.hdxpysbbn) {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.pgo0c5f-d) {
  d: path("M3.808 22.193a1 1 0 0 1 0-1.415l16.97-16.97a1 1 0 1 1 1.414 1.414l-16.97 16.97a1 1 0 0 1-1.414 0");
}

</style>
