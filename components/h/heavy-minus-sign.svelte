<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c700cvb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:heavy-minus-sign" {...props}></Icon>
<style>
:global(.c700cvb5n) {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M2 26h60v12H2z");
}

</style>
