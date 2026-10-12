<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y9i8a_b1f"/><path class="m8nxf_9ht"/><circle class="v1wf5pbfy"/><path class="n2554bvcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:license-sharp" {...props}></Icon>
<style>
:global(.m8nxf_9ht) {
  d: path("M13.75 2.75v5.5h5.5m-11 3h4m-4 3.25h2.5");
}

:global(.n2554bvcg) {
  d: path("M15.5 18.25v3l1.5-1l1.5 1v-3");
}

:global(.v1wf5pbfy) {
  cx: 17px;
  cy: 15.75px;
  r: 2.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9i8a_b1f) {
  d: path("M12.75 21.25h-8V2.75h9l5.5 5.5V12");
}

</style>
