<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q5amowf4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:down-right-arrow" {...props}></Icon>
<style>
:global(.q5amowf4h) {
  fill: currentColor;
  d: path("M53.213 10.786c-11.715-11.715-30.71-11.715-42.425 0c-11.717 11.717-11.717 30.711 0 42.426c11.715 11.717 30.71 11.717 42.425 0c11.715-11.715 11.715-30.709 0-42.426M45 44.999H22.874l7.345-7.563L17 24.044l6.956-7.045l13.458 13.283L45 22.866z");
}

</style>
