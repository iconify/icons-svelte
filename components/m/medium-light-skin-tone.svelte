<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="s-t8usfrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:medium-light-skin-tone" {...props}></Icon>
<style>
:global(.s-t8usfrs) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--fed0ac, #fed0ac);
}

</style>
