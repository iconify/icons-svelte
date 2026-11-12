<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_x9xmbd"/><path class="c-ivyjb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-bold-duotone" {...props}></Icon>
<style>
:global(.c-ivyjb8c) {
  fill: currentColor;
  d: path("M8.00012 11.2929L8.00012 5.5703C8.00012 5.04189 8.79106 4.79869 9.20479 5.1999L11.6865 7.60648L8.00012 11.2929Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.f6_x9xmbd) {
  fill: currentColor;
  d: path("M12.4044 8.30273L15.8351 11.6296C16.0549 11.8428 16.0549 12.1573 15.8351 12.3704L9.20467 18.8001C8.79094 19.2013 8 18.9581 8 18.4297V12.7071L12.4044 8.30273Z");
}

</style>
