<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="kj73mib-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:red-circle" {...props}></Icon>
<style>
:global(.kj73mib-f) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

</style>
