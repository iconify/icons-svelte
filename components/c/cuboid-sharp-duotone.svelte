<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hucznl23t"/><path class="el2u1yvhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cuboid-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.el2u1yvhp) {
  d: path("M2 9L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929L7.2929 2.2929C7.4804 2.1054 7.7348 2 8 2L21 2C21.5523 2 22 2.4477 22 3L22 3.4142L16.7071 8.7071C16.5196 8.8946 16.2652 9 16 9L2 9Z");
}

:global(.hucznl23t) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 7.2929L7.2929 2.2929C7.4804 2.1054 7.7348 2 8 2L21 2C21.5523 2 22 2.4477 22 3L22 16C22 16.2652 21.8946 16.5196 21.7071 16.7071L16.7071 21.7071C16.5196 21.8946 16.2652 22 16 22L3 22C2.4477 22 2 21.5523 2 21L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929Z");
}

</style>
