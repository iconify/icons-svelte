<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lriubg22d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:large-orange-diamond" {...props}></Icon>
<style>
:global(.lriubg22d) {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M63 32L32 62.998L1 32L32 1");
}

</style>
