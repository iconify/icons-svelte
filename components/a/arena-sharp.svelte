<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o0ktwi0vi"/><path class="fepgsabyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arena-sharp" {...props}></Icon>
<style>
:global(.fepgsabyj) {
  d: path("M5.5 21.25V18.5h2v2.75m3.5 0V18.5h2v2.75m3.5 0V18.5h2v2.75");
}

:global(.o0ktwi0vi) {
  d: path("M2.75 20.75V7.5H5v3h2.25v3H9.5v3h5v-3h2.25v-3H19v-3h2.25v13.75H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
