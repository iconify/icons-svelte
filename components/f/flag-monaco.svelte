<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="byiqteejc"/><path class="drwyycbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-monaco" {...props}></Icon>
<style>
:global(.byiqteejc) {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 18v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9z");
}

:global(.drwyycbim) {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 5H4a4 4 0 0 0-4 4v9h36V9a4 4 0 0 0-4-4");
}

</style>
