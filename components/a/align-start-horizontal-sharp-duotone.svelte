<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cb7un5lwg"/><path class="hz81xnw_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-start-horizontal-sharp-duotone" {...props}></Icon>
<style>
:global(.cb7un5lwg) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 5C10.552 5 11 5.448 11 6V22C11 22.552 10.552 23 10 23H4C3.448 23 3 22.552 3 22V6C3 5.448 3.448 5 4 5H10ZM20 5C20.552 5 21 5.448 21 6V14C21 14.552 20.552 15 20 15H14C13.448 15 13 14.552 13 14V6C13 5.448 13.448 5 14 5H20Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hz81xnw_g) {
  d: path("M23 1V3H1V1H23Z");
}

</style>
