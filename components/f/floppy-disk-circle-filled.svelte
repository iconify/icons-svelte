<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG3mrAEVec"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="yu9-2dedx"/><path class="cn3yymb1n"/></g></mask></defs><circle mask="url(#SVG3mrAEVec)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:floppy-disk-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.cn3yymb1n) {
  d: path("M8 14a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v7h-2v-7h-6v7H8zm.5-6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V6a1 1 0 1 0-2 0v2h-4V6a1 1 0 0 0-2 0z");
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

:global(.yu9-2dedx) {
  d: path("M4.5 6.5a2 2 0 0 1 2-2h10.586a2 2 0 0 1 1.414.586L20.914 7.5a2 2 0 0 1 .586 1.414V19.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2zm2 0v13h13V8.914L17.086 6.5z");
}

</style>
