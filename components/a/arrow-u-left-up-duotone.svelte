<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="r2tjq9luz"/><path class="z_gc4cptl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-u-left-up-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.r2tjq9luz) {
  d: path("M136 80H40l48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_gc4cptl) {
  d: path("M200 72a8 8 0 0 0-8 8v88a48 48 0 0 1-96 0V88h40a8 8 0 0 0 5.66-13.66l-48-48a8 8 0 0 0-11.32 0l-48 48A8 8 0 0 0 40 88h40v80a64 64 0 0 0 128 0V80a8 8 0 0 0-8-8M88 43.31L116.69 72H59.31Z");
}

</style>
