<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ym28i0ipj"/><path class="nmlij9bln"/><path class="femcarbuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-down" {...props}></Icon>
<style>
:global(.femcarbuu) {
  d: path("M10 14a1 1 0 0 1-1-1V5a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.nmlij9bln) {
  d: path("M5.232 11.027a1 1 0 0 1 1.408-.129l4 3.334a1 1 0 1 1-1.28 1.536l-4-3.333a1 1 0 0 1-.128-1.408");
}

:global(.ym28i0ipj) {
  d: path("M14.768 11.027a1 1 0 0 1-.128 1.408l-4 3.333a1 1 0 0 1-1.28-1.536l4-3.334a1 1 0 0 1 1.408.129");
}

</style>
