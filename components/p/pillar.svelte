<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ia1c-wqff"><path class="c1czy_9xl"/><path class="zwce0gsxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pillar" {...props}></Icon>
<style>
:global(.c1czy_9xl) {
  d: path("M9.136 21L5.7 17.625V14.25h9.164V3L18.3 6.375v11.25H9.136z");
}

:global(.ia1c-wqff) {
  fill: var(--svg-color--9601d9, #9601d9);
}

:global(.zwce0gsxs) {
  d: path("M10.282 5.25H5.7v4.5h4.582z");
}

</style>
