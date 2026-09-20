<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="jyo12bpqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:brown-circle" {...props}></Icon>
<style>
:global(.jyo12bpqb) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--c1694f, #c1694f);
}

</style>
