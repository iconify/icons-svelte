<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="lzpq-ccsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:red-circle" {...props}></Icon>
<style>
:global(.lzpq-ccsc) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: currentColor;
}

</style>
