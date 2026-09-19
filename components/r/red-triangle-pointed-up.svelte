<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ep3is9lch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:red-triangle-pointed-up" {...props}></Icon>
<style>
:global(.ep3is9lch) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2L2 62h60z");
}

</style>
