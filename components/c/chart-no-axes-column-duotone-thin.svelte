<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flg13-sml"/><path class="ai1ljvb5z"/><path class="f3-bt7bzp"/><path class="u66cvxjqz"/><path class="h-el3xdlg"/><path class="e9_u-df3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-no-axes-column-duotone-thin" {...props}></Icon>
<style>
:global(.ai1ljvb5z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e9_u-df3m) {
  d: path("M18 13v7");
}

:global(.f3-bt7bzp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flg13-sml) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-el3xdlg) {
  d: path("M12 6v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u66cvxjqz) {
  d: path("M6 10v10");
}

</style>
