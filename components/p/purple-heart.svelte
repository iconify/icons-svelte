<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bkgh1pbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:purple-heart" {...props}></Icon>
<style>
:global(.bkgh1pbzb) {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M61.1 18.2c-6.4-17-27.2-9.4-29.1-.9c-2.6-9-22.9-15.7-29.1.9C-4 36.7 29.6 53.3 32 56c2.4-2.2 36-19.6 29.1-37.8");
}

</style>
