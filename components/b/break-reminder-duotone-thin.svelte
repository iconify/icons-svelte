<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="icnat23co"/><path class="s3r-7pbpm"/><path class="llew0ibxe"/><path class="zcykq5u6t"/><path class="r57e8zbzz"/><path class="ng_tlibuk"/><path class="s0v-_1bji"/><path class="v9hia4w8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:break-reminder-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icnat23co) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9v9h11V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.llew0ibxe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ng_tlibuk) {
  d: path("M15 9a3 3 0 0 1 0 6");
}

:global(.r57e8zbzz) {
  d: path("M4 9v9h11V9");
}

:global(.s0v-_1bji) {
  d: path("M7 3a3 3 0 0 1 0 6");
}

:global(.s3r-7pbpm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v9hia4w8h) {
  d: path("M12 3a3 3 0 0 1 0 6");
}

:global(.zcykq5u6t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
