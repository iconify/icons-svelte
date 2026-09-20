<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="j98fdby5a"/><path class="n1lshobfw"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="i1jp0gbac"/><path class="emoyz4b2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deadline-missed-duotone-thin" {...props}></Icon>
<style>
:global(.d1sql1bsn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.emoyz4b2o) {
  d: path("m15 11 -6 6");
}

:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1jp0gbac) {
  d: path("m9 11 6 6");
}

:global(.j98fdby5a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 11 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.n1lshobfw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 11 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rr5s23bmj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tqek15bkw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
