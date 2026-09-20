<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="egg85qpdp"/><path class="udl6y4m_q"/><path class="pi6hjtb_h"/><path class="nb6vs4w1b"/><path class="hppiisbif"/><path class="hb_6svr8j"/><path class="bi34yzw-v"/><path class="urzumpb2c"/><path class="qowfo405a"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:city-view-duotone-thin" {...props}></Icon>
<style>
:global(.bi34yzw-v) {
  d: path("M12 21V4h7v17");
}

:global(.egg85qpdp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21V10h7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hb_6svr8j) {
  d: path("M3 21V10h7v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hppiisbif) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nb6vs4w1b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.pi6hjtb_h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qowfo405a) {
  d: path("M12 9h7");
}

:global(.udl6y4m_q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 21V4h7v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.urzumpb2c) {
  d: path("M3 14h7");
}

</style>
