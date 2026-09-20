<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="n0h4viywf"/><path class="xpy8sjkzl"/><path class="guflwugwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-ireland" {...props}></Icon>
<style>
:global(.guflwugwf) {
  fill: var(--svg-color--ff883e, #ff883e);
  d: path("M32 5h-8v26h8a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.n0h4viywf) {
  fill: var(--svg-color--169b62, #169b62);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

:global(.xpy8sjkzl) {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

</style>
