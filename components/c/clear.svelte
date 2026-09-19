<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtk-kuxcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:clear" {...props}></Icon>
<style>
:global(.qtk-kuxcr) {
  fill: currentColor;
  d: path("M19 6.41L17.59 5L12 10.59L6.41 5L5 6.41L10.59 12L5 17.59L6.41 19L12 13.41L17.59 19L19 17.59L13.41 12z");
}

</style>
