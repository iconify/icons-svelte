<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="jaca2pbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:medium-skin-tone" {...props}></Icon>
<style>
:global(.jaca2pbta) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--d6a57c, #d6a57c);
}

</style>
