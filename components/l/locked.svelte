<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="kuhfyzbzs"/><path class="gdwmsnb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:locked" {...props}></Icon>
<style>
:global(.gdwmsnb0w) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M32 32a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V18a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4z");
}

:global(.kuhfyzbzs) {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M18 0C12.477 0 8 4.477 8 10v10h4V10a6 6 0 0 1 12 0v10h4V10c0-5.523-4.477-10-10-10");
}

</style>
