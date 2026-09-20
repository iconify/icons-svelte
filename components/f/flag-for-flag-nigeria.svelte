<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ej6l47bly"/><path class="xpy8sjkzl"/><path class="x1ep41boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-flag-nigeria" {...props}></Icon>
<style>
:global(.ej6l47bly) {
  fill: var(--svg-color--009a49, #009a49);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.x1ep41boo) {
  fill: var(--svg-color--009a49, #009a49);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.xpy8sjkzl) {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

</style>
