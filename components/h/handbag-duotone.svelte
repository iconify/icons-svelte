<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fp47fhmkf"/><path class="z2hiwsnbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handbag-duotone" {...props}></Icon>
<style>
:global(.fp47fhmkf) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 8h10c1.098.001 1.871.976 2 2l1 8c.133 1.062-.336 2-1 2H5c-.664 0-1.133-.938-1-2l1-8c.129-1.024.902-1.999 2-2");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.z2hiwsnbi) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h5c1 0 1.857.857 2 2l1 8c.133 1.062-.336 2-1 2H5c-.664 0-1.133-.938-1-2l1-8c.143-1.143 1-2 2-2zM8 8a4 4 0 1 1 8 0");
}

</style>
