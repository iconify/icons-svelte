<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="xaz90clio"/><path class="ah2gkhstn"/><path class="f3be8jb4e"/><path class="b6a_ln9rl"/><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="o759xmblc"/><path class="wew0vnk_n"/><path class="k7cz9qivc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-data-duotone-bold" {...props}></Icon>
<style>
:global(.ah2gkhstn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b6a_ln9rl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f3be8jb4e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7vr07ufd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.k7cz9qivc) {
  d: path("M18 11v5");
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wew0vnk_n) {
  d: path("M12 5v14");
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
