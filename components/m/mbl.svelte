<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="kfo2910sv"><path class="knzib4sih"/><path class="b6fs05qmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mbl" {...props}></Icon>
<style>
:global(.b6fs05qmm) {
  d: path("M21 5.813L8.625 8.18v7.74L21 18.187z");
}

:global(.kfo2910sv) {
  fill: var(--svg-color--5b449b, #5b449b);
}

:global(.knzib4sih) {
  d: path("M3 19.875V4.125l10.125 1.997l-4.5.815l-3.938-.815V17.85l3.938-.788l4.5.788z");
}

</style>
