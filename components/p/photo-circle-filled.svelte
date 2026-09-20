<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG3rXSqzbZ"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="iumt0lbxf"/><path class="ydffvacoz"/><path clip-rule="evenodd" class="ex17wkb-a"/><path class="droxnd8cg"/><path clip-rule="evenodd" class="k0y8y2pmd"/><path clip-rule="evenodd" class="zhnl7lbmw"/></g></mask></defs><circle mask="url(#SVG3rXSqzbZ)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:photo-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.droxnd8cg) {
  d: path("M13.494 12.123a1 1 0 0 1 1.512 0l3.007 3.472a1 1 0 0 1-.756 1.655h-6.014a1 1 0 0 1-.756-1.655z");
}

:global(.ex17wkb-a) {
  fill-rule: evenodd;
  d: path("m10.5 14.517l-.916 1.233h1.832zm.803-1.435a1 1 0 0 0-1.606 0l-1.91 2.572a1 1 0 0 0 .804 1.596h3.818a1 1 0 0 0 .803-1.596z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iumt0lbxf) {
  fill-rule: evenodd;
  d: path("M11 12a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

:global(.ivjvz2eii) {
  fill: var(--svg-color--000, #000);
}

:global(.k0y8y2pmd) {
  fill-rule: evenodd;
  d: path("m14.25 13.541l-1.913 2.209h3.826zm.756-1.418a1 1 0 0 0-1.512 0l-3.007 3.472a1 1 0 0 0 .756 1.655h6.014a1 1 0 0 0 .756-1.655z");
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.ydffvacoz) {
  d: path("M9.697 13.082a1 1 0 0 1 1.606 0l1.91 2.572a1 1 0 0 1-.804 1.596H8.591a1 1 0 0 1-.803-1.596z");
}

:global(.zhnl7lbmw) {
  fill-rule: evenodd;
  d: path("M6.5 6.5v13h13v-13zm-.5-2A1.5 1.5 0 0 0 4.5 6v14A1.5 1.5 0 0 0 6 21.5h14a1.5 1.5 0 0 0 1.5-1.5V6A1.5 1.5 0 0 0 20 4.5z");
}

</style>
