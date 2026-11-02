<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wnm6_4bbd"/><path class="zpozd_xgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:receipt-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.wnm6_4bbd) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 3a2 2 0 0 1 2 2v15c0 .369-.631.369-1 0a1.415 1.415 0 0 0-2 0a1.415 1.415 0 0 1-2 0a1.415 1.415 0 0 0-2 0a1.415 1.415 0 0 1-2 0a1.415 1.415 0 0 0-2 0a1.415 1.415 0 0 1-2 0a1.415 1.415 0 0 0-2 0c-.369.369-1 .369-1 0V5a2 2 0 0 1 2-2Z");
}

:global(.zpozd_xgk) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h6a2 2 0 0 1 2 2v15c0 .369-.631.369-1 0a1.414 1.414 0 0 0-2 0a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 0-2 0a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 0-2 0a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 0-2 0c-.369.369-1 .369-1 0V5a2 2 0 0 1 2-2zM8 7h8m-8 4h8m-8 4h4");
}

</style>
