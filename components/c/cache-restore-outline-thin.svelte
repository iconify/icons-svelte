<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b0hkzgbgd"/><path class="wuk2mlziz"/><path class="nb_catcjy"/><path class="z0ud8rb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cache-restore-outline-thin" {...props}></Icon>
<style>
:global(.b0hkzgbgd) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nb_catcjy) {
  d: path("M12 7v6");
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.z0ud8rb7a) {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
