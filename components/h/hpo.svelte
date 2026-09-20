<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f20p0qbhq"/><path class="f2uqn3bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hpo" {...props}></Icon>
<style>
:global(.f20p0qbhq) {
  fill: var(--svg-color--000, #000);
  d: path("M13.589 10.412V3h-3.177v7.412zm0 3.176v-3.176H21v3.176zm0 0V21h-3.177v-7.412z");
}

:global(.f2uqn3bht) {
  fill: var(--svg-color--106bff, #106bff);
  d: path("M3 10.41h7.412v3.177H3z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
