<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="nbsa7ej7t"/><path class="xpy8sjkzl"/><path class="ccym0498h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-cote-divoire" {...props}></Icon>
<style>
:global(.ccym0498h) {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.nbsa7ej7t) {
  fill: var(--svg-color--f77f00, #f77f00);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.xpy8sjkzl) {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

</style>
