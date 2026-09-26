<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v5tw_dbxe"/><path class="xs7teru1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-create-arrow-fill" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v5tw_dbxe) {
  d: path("M6 21V9M14 6H16C17.1046 6 18 6.89543 18 8V12M14.7929 4L13.1465 5.64645C12.9512 5.84171 12.9512 6.15829 13.1465 6.35355L14.7929 8M18.5 16V21M16 18.5H21");
}

:global(.xs7teru1d) {
  fill: currentColor;
  d: path("M10 6C10 8.20914 8.20914 10 6 10C3.79086 10 2 8.20914 2 6C2 3.79086 3.79086 2 6 2C8.20914 2 10 3.79086 10 6Z");
  stroke: none;
}

</style>
