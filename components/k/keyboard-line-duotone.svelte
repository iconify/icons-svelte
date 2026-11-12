<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="klim778ja"/><path class="l6fc-_mup"/><path class="spg89f-kh"/><path class="a9qq5obmi"/><path class="onf2o-04e"/><path class="ghi5_wb7c"/><path class="qow0sabwa"/><path class="bzz63mbuk"/><path class="l6v81ebtl"/><path class="kq4zr17pd"/><path class="tzrqxpbtp"/><path class="gh62wjbhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:keyboard-line-duotone" {...props}></Icon>
<style>
:global(.a9qq5obmi) {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.bzz63mbuk) {
  stroke-linejoin: round;
  d: path("M18 12H18.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.gh62wjbhx) {
  stroke-linejoin: round;
  d: path("M6 12H6.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ghi5_wb7c) {
  stroke-linejoin: round;
  d: path("M15 9H15.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klim778ja) {
  d: path("M8 19H16C18.8284 19 20.2426 19 21.1213 18.1213C22 17.2426 22 15.8284 22 13V11C22 8.17157 22 6.75736 21.1213 5.87868C20.2426 5 18.8284 5 16 5H8C5.17157 5 3.75736 5 2.87868 5.87868C2 6.75736 2 8.17157 2 11V13C2 15.8284 2 17.2426 2.87868 18.1213C3.75736 19 5.17157 19 8 19Z");
}

:global(.kq4zr17pd) {
  stroke-linejoin: round;
  d: path("M12 12H12.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.l6fc-_mup) {
  d: path("M7 16H17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.l6v81ebtl) {
  stroke-linejoin: round;
  d: path("M15 12H15.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.onf2o-04e) {
  stroke-linejoin: round;
  d: path("M12 9H12.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.qow0sabwa) {
  stroke-linejoin: round;
  d: path("M18 9H18.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.spg89f-kh) {
  stroke-linejoin: round;
  d: path("M6 9H6.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.tzrqxpbtp) {
  stroke-linejoin: round;
  d: path("M9 12H9.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
