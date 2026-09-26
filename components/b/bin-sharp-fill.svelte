<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inyb3balg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bin-sharp-fill" {...props}></Icon>
<style>
:global(.inyb3balg) {
  fill: currentColor;
  d: path("M21 8L19 8L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 8L3 8L3 6L21 6L21 8ZM15 3L9 3L9 1L15 1L15 3Z");
}

</style>
