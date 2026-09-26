<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="drtd24r2m"/><path class="ka7bdnkoz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-two-tone" {...props}></Icon>
<style>
:global(.drtd24r2m) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 7C1 4.7909 2.7909 3 5 3H19C21.2091 3 23 4.7909 23 7V17C23 19.2091 21.2091 21 19 21H5C2.7909 21 1 19.2091 1 17V7Z");
  stroke: none;
}

:global(.ka7bdnkoz) {
  d: path("M2 9H22M2 7C2 5.3431 3.3431 4 5 4H19C20.6569 4 22 5.3431 22 7V17C22 18.6569 20.6569 20 19 20H5C3.3431 20 2 18.6569 2 17V7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
