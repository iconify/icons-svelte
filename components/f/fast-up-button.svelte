<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vqusuabbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:fast-up-button" {...props}></Icon>
<style>
:global(.vqusuabbu) {
  fill: currentColor;
  d: path("M53.214 10.787c-11.715-11.715-30.711-11.715-42.426 0c-11.717 11.717-11.717 30.711 0 42.426c11.715 11.715 30.711 11.715 42.426 0s11.715-30.71 0-42.426m-3.213 35.211h-36L25.88 33.279H14.001l18-19.28l18 19.28H38.122z");
}

</style>
