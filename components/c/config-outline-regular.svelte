<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="jtt8g10_o"/><path class="ewubqf5qj"/><path class="ae0h5kb0o"/><path class="m9-_5v7jw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:config-outline-regular" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.ewubqf5qj) {
  d: path("M13 8v4");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.m9-_5v7jw) {
  d: path("M11 13v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
