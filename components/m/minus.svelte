<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zjkn9acpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:minus" {...props}></Icon>
<style>
:global(.zjkn9acpk) {
  fill: var(--svg-color--405866, #405866);
  d: path("M58.05 26.705H5.82c-7.75 0-7.75 12.02 0 12.02h52.23c7.752 0 7.752-12.02 0-12.02");
}

</style>
