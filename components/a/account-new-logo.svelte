<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5knkkbtr"/><path class="q4w-yq62n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-new-logo" {...props}></Icon>
<style>
:global(.q4w-yq62n) {
  d: path("M7 21.5v-4h3v4m9-6.75q.25 3 2.75 3.25q-2.5.25-2.75 3.25q-.25-3-2.75-3.25q2.5-.25 2.75-3.25Z");
}

:global(.s5knkkbtr) {
  d: path("M3 2.5h11v19H3Zm3.75 4h.01m3.49 0h.01M6.75 10h.01m3.49 0h.01m-3.51 3.5h.01m3.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
