<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-z-pg5fi"/><path class="d4s3zxbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-castle" {...props}></Icon>
<style>
:global(.d4s3zxbdv) {
  d: path("M10 20v-4q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T12 14q.146 0 .29.021q.145.021.285.063t.272.104t.254.142t.231.178t.202.209t.17.236t.134.259M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-z-pg5fi) {
  d: path("M13.9 20H3V3.5h5V8h2v2h4V8h2V3.5h5v8.9");
}

</style>
