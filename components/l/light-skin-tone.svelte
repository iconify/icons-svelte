<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="o6fhpyk-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:light-skin-tone" {...props}></Icon>
<style>
:global(.o6fhpyk-a) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffe1bd, #ffe1bd);
}

</style>
