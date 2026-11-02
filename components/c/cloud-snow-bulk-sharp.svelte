<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0k3xpq5f"/><path class="zts903b_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-snow-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.u0k3xpq5f) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 16a5 5 0 0 1-4.987-4.646a5 5 0 0 1 4.282-5.305a6.58 6.58 0 0 1 2.773-3.121a6.75 6.75 0 0 1 4.33-.792c2.381.358 4.323 1.911 5.151 4.18c.21.58.346 1.184.407 1.799A4 4 0 0 1 18 16Z");
}

:global(.zts903b_a) {
  d: path("M8.01 17a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-6 3a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Z");
}

</style>
