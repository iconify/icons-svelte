<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="t3j029b6z"><path class="zp957qwgn"/><path class="k7zwcnbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:bolt" {...props}></Icon>
<style>
:global(.k7zwcnbrs) {
  d: path("M21 3L7.2 8.192l5.838 4.847L3 21l13.5-5.193l-1.385-7.961z");
}

:global(.t3j029b6z) {
  fill: var(--svg-color--280c9c, #280c9c);
}

:global(.zp957qwgn) {
  d: path("M7.2 17.196v-8.56l5.28 4.404z");
}

</style>
