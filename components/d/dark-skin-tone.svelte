<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="kwv23tbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:dark-skin-tone" {...props}></Icon>
<style>
:global(.kwv23tbku) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--8a6859, #8a6859);
}

</style>
