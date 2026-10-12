<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jbhk_vbwl"/><path class="nw-pemb9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:inboxes-sharp" {...props}></Icon>
<style>
:global(.jbhk_vbwl) {
  d: path("m2.75 13.25l2.6-7.4l.625-1.619l1.735.019h8.58l1.735-.019l.625 1.619l2.6 7.4v7H2.75v-2.5Z");
}

:global(.nw-pemb9z) {
  d: path("M2.75 13.25h4.4l1.1 2.2l.4.8h6.7l.4-.8l1.1-2.2h4.4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
