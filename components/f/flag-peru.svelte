<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="uu8btdbmm"/><path class="xpy8sjkzl"/><path class="eefkjlb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-peru" {...props}></Icon>
<style>
:global(.eefkjlb0g) {
  fill: var(--svg-color--d91023, #d91023);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.uu8btdbmm) {
  fill: var(--svg-color--d91023, #d91023);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.xpy8sjkzl) {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

</style>
