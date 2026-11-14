<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cuwf8hb0u"/><path class="fkn2dzb9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:one-person-tent" {...props}></Icon>
<style>
:global(.cuwf8hb0u) {
  d: path("M13.328 17H2.5C2.5 1.933 17.425.22 20.819 11.861");
}

:global(.fkn2dzb9n) {
  d: path("M7 17c0-5.5 5-5.5 5 0m4-1.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
