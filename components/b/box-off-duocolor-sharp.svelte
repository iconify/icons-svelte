<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nn5ugzt-g"/><path class="nkbathbby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:box-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.nkbathbby) {
  d: path("M4.636 5.636L3 6.444v11.112L12 22l6.025-2.975M8.423 3.766L12 2l9 4.444v9.9");
}

:global(.nn5ugzt-g) {
  stroke-opacity: 0.4;
  d: path("M3 6.444L7.83 8.83M12 13v9m2.374-12.283L21 6.444M2 3l19 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
