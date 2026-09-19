<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="zftiqseks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:blue-circle" {...props}></Icon>
<style>
:global(.zftiqseks) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--0071bc, #0071bc);
}

</style>
