<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nm2qqyyyd"/><path class="gyaiv24xg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:meter-water-duocolor-sharp" {...props}></Icon>
<style>
:global(.gyaiv24xg) {
  d: path("M5 3h14v18H5Zm-2 9h2m14 0h2");
}

:global(.nm2qqyyyd) {
  stroke-opacity: 0.4;
  d: path("M12 6.857s-4 2.857-4 6.286a4 4 0 0 0 8 0c0-3.429-4-6.286-4-6.286");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
