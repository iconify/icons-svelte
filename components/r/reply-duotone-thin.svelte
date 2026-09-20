<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-d1yibvp"/><path class="icjgng4dc"/><path class="pzovgl99o"/><path class="q5w-xob0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reply-duotone-thin" {...props}></Icon>
<style>
:global(.h-d1yibvp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4 3 9l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icjgng4dc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pzovgl99o) {
  d: path("M8 4 3 9l5 5");
}

:global(.q5w-xob0a) {
  d: path("M3 9h14v11");
}

</style>
