<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bo8u7q83r"/><path class="zrdou8b0n"/><path class="j8_8pdbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:margin-outline-regular" {...props}></Icon>
<style>
:global(.bo8u7q83r) {
  d: path("M21 12a9 9 0 1 1 -9 -9");
}

:global(.j8_8pdbyc) {
  d: path("M12 3v9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>
