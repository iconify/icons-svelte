<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gxql29beq"/><path class="srht4eb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-designer-sharp" {...props}></Icon>
<style>
:global(.gxql29beq) {
  d: path("M12 2.75c5.1 0 9.25 3.6 9.25 8c0 2.6-2.1 4.25-4.5 4.25h-2a1.75 1.75 0 0 0-1.25 3c.75.85.25 3.25-1.5 3.25c-5.1 0-9.25-4.15-9.25-9.25S6.9 2.75 12 2.75Z");
}

:global(.srht4eb0a) {
  d: path("M7.5 9.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m.75 5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m6-8.75l.36 2.64l2.64.36l-2.64.36l-.36 2.64l-.36-2.64l-2.64-.36l2.64-.36z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
