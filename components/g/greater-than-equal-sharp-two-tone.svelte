<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g51j9bcto"/><path clip-rule="evenodd" class="kl4zvkbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:greater-than-equal-sharp-two-tone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.g51j9bcto) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.53 9.15C16.823 9.33 17 9.66 17 10C17 10.34 16.822 10.66 16.53 10.85L8.06 16.14L7.53 15.29L7 14.45L14.112 10L7.227 5.7L8.287 4L16.53 9.15Z");
}

:global(.kl4zvkbzg) {
  fill-rule: evenodd;
  d: path("M17 18V20H7V18H17Z");
}

</style>
