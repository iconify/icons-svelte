<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="b7yw7z1gn"/><path class="bkdjfsbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:angle-up" {...props}></Icon>
<style>
:global(.b7yw7z1gn) {
  d: path("m15.36 13.268l-6-5c-1.025-.853.256-2.39 1.28-1.536l6 5c1.024.853-.256 2.39-1.28 1.536");
}

:global(.bkdjfsbgo) {
  d: path("m3.36 11.732l6-5c1.024-.854 2.305.683 1.28 1.536l-6 5c-1.024.854-2.305-.683-1.28-1.536");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
