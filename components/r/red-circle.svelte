<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="yvb0blvjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:red-circle" {...props}></Icon>
<style>
:global(.yvb0blvjs) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

</style>
