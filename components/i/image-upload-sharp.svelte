<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><circle class="p_flhjbml"/><path class="k3sx1jb3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:image-upload-sharp" {...props}></Icon>
<style>
:global(.k3sx1jb3z) {
  d: path("m2.75 16.25l4.1-4.1l1.125-1.112L9.1 12.15l5.15 5.15M13 16.05l1.85-1.85l1.125-1.112L17.1 14.2l3.9 3.9");
}

:global(.p_flhjbml) {
  cx: 8.5px;
  cy: 9px;
  r: 1.75px;
}

:global(.pw7p-85ys) {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
