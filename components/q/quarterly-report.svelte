<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h81zrmtfz"/><path class="nl9nuxcnn"/><path class="hcr7wigqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quarterly-report" {...props}></Icon>
<style>
:global(.h81zrmtfz) {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hcr7wigqs) {
  d: path("M12.75 13.25v-3.5a3.5 3.5 0 0 1 3.5 3.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nl9nuxcnn) {
  d: path("M8.5 6.25h7M12 9.75A4.25 4.25 0 1 0 16.25 14");
}

</style>
