<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cagzvcbxe"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:galaxy" {...props}></Icon>
<style>
:global(.cagzvcbxe) {
  d: path("M12 8.5c.3-.05 1.15-.38 1.78-.32c.63.05 1.39.25 2 .65c.62.39 1.27.99 1.68 1.71c.42.71.76 1.64.82 2.57c.06.92-.07 2.02-.47 2.96c-.39.94-1.06 1.96-1.9 2.7c-.85.73-1.99 1.41-3.17 1.73c-1.17.32-3.25.16-3.9.19M12 15.5c-.3.05-1.15.38-1.78.32c-.63-.05-1.39-.25-2-.65c-.62-.39-1.27-.99-1.68-1.71c-.42-.71-.76-1.64-.82-2.57c-.06-.92.07-2.02.47-2.96c.39-.94 1.06-1.96 1.9-2.7c.85-.73 1.99-1.41 3.17-1.73c1.17-.32 3.25-.16 3.9-.19");
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
