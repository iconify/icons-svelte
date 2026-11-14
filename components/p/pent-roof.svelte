<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q-ngx-bes"/><path class="dgwuiea8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pent-roof" {...props}></Icon>
<style>
:global(.dgwuiea8m) {
  d: path("M4.5 7v13.5h15v-9.75");
}

:global(.q-ngx-bes) {
  d: path("m2.5 3.5l19 4.75v3L2.5 6.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
