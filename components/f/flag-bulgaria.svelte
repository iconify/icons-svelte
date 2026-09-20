<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="fnfhbcb1w"/><path class="qetqtn6tv"/><path class="i_yyqxbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-bulgaria" {...props}></Icon>
<style>
:global(.fnfhbcb1w) {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

:global(.i_yyqxbzn) {
  fill: var(--svg-color--00966e, #00966e);
  d: path("M0 14h36v8H0z");
}

:global(.qetqtn6tv) {
  fill: var(--svg-color--d62612, #d62612);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H0z");
}

</style>
