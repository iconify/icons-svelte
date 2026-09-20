<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="apxht593w"/><path class="arudnqcpi"/><path class="qczurlbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-guinea" {...props}></Icon>
<style>
:global(.apxht593w) {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.arudnqcpi) {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M12 5h12v26H12z");
}

:global(.qczurlbnk) {
  fill: var(--svg-color--009460, #009460);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

</style>
