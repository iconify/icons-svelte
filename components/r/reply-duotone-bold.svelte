<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nvmmdk07k"/><path class="b0kaw4fzr"/><path class="pzovgl99o"/><path class="q5w-xob0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reply-duotone-bold" {...props}></Icon>
<style>
:global(.b0kaw4fzr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nvmmdk07k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4 3 9l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pzovgl99o) {
  d: path("M8 4 3 9l5 5");
}

:global(.q5w-xob0a) {
  d: path("M3 9h14v11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
