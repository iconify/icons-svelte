<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e2ea05ihx"/><path class="ivymbgoxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-three-quarter-duotone" {...props}></Icon>
<style>
:global(.e2ea05ihx) {
  stroke-opacity: 0.4;
  d: path("M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

:global(.ivymbgoxe) {
  d: path("M12 22C6.4772 22 2 17.5229 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
