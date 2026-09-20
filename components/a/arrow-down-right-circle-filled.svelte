<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGg1Apmbaz"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="xw6869ieq"/><path class="pq-n8ab6e"/><path class="y1bwxq1rz"/></g></mask></defs><circle mask="url(#SVGg1Apmbaz)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-down-right-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
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

:global(.pq-n8ab6e) {
  d: path("M10.354 17.098a1 1 0 0 1 .906-1.087l5.185-.471a1 1 0 1 1 .181 1.991l-5.185.472a1 1 0 0 1-1.087-.905");
}

:global(.xw6869ieq) {
  d: path("M17.098 10.354a1 1 0 0 1 .905 1.087l-.472 5.185a1 1 0 1 1-1.991-.18l.471-5.186a1 1 0 0 1 1.087-.906");
}

:global(.y1bwxq1rz) {
  d: path("M15.828 15.829a1 1 0 0 1-1.414 0l-5.657-5.657a1 1 0 1 1 1.415-1.415l5.656 5.657a1 1 0 0 1 0 1.415");
}

</style>
