<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="dzoyk5cfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-zoom-out-bold-duotone" {...props}></Icon>
<style>
:global(.aygw_60rm) {
  fill: currentColor;
  d: path("M11.157 20.313a9.157 9.157 0 1 0 0-18.313a9.157 9.157 0 0 0 0 18.313");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.dzoyk5cfz) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.023 11.157c0-.4.324-.723.723-.723h4.82a.723.723 0 1 1 0 1.445h-4.82a.723.723 0 0 1-.723-.723m10.816 7.683a.723.723 0 0 1 1.022 0l1.928 1.927a.723.723 0 0 1-1.023 1.023L18.84 19.86a.723.723 0 0 1 0-1.022");
}

</style>
