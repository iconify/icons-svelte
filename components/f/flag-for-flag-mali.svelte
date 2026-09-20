<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="dit4mcb9r"/><path class="arudnqcpi"/><path class="ae9eq6qay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-mali" {...props}></Icon>
<style>
:global(.ae9eq6qay) {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.arudnqcpi) {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M12 5h12v26H12z");
}

:global(.dit4mcb9r) {
  fill: var(--svg-color--14b53a, #14b53a);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

</style>
