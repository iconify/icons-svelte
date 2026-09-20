<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jhfnm669a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:grid-four-bold" {...props}></Icon>
<style>
:global(.jhfnm669a) {
  fill: currentColor;
  d: path("M200 36H56a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 80h-56V60h56Zm-80-56v56H60V60Zm-56 80h56v56H60Zm80 56v-56h56v56Z");
}

</style>
