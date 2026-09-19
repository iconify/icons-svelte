<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m_-w-djsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:heavy-plus-sign" {...props}></Icon>
<style>
:global(.m_-w-djsn) {
  fill: currentColor;
  d: path("M38 26V2H26v24H2v12h24v24h12V38h24V26z");
}

</style>
