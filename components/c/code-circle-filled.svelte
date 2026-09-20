<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGkpwpHlch"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="y4h93hqid"/><path class="ajm7rweub"/><path class="cgiib2r5z"/></g></mask></defs><circle mask="url(#SVGkpwpHlch)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:code-circle-filled" {...props}></Icon>
<style>
:global(.ajm7rweub) {
  d: path("M9.41 9.331a1 1 0 0 1-.074 1.412l-3.334 3a1 1 0 1 1-1.338-1.486l3.334-3a1 1 0 0 1 1.412.074m12 3a1 1 0 0 1-.074 1.412l-3.334 3a1 1 0 1 1-1.338-1.486l3.334-3a1 1 0 0 1 1.412.074");
}

:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.cgiib2r5z) {
  d: path("M16.59 9.331a1 1 0 0 1 1.412-.074l3.334 3a1 1 0 0 1-1.338 1.486l-3.334-3a1 1 0 0 1-.074-1.412m-1.827-2.796a1 1 0 0 1 .702 1.228l-3 11a1 1 0 0 1-1.93-.526l3-11a1 1 0 0 1 1.228-.702");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.kvn14gsjy) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

:global(.y4h93hqid) {
  d: path("M4.59 12.331a1 1 0 0 1 1.412-.074l3.334 3a1 1 0 0 1-1.338 1.486l-3.334-3a1 1 0 0 1-.074-1.412");
}

</style>
