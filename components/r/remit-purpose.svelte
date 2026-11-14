<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w02ta8btp"/><path class="au6_zk5ea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:remit-purpose" {...props}></Icon>
<style>
:global(.au6_zk5ea) {
  d: path("M15 15h3.25l3 3L18 21.25l-3-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w02ta8btp) {
  d: path("m12.746 19.978l-.246.522L10 15l-6.5-3.5l17-8l-4.093 8.697M10 15l2.225-2.437m.337-.369L20.5 3.5");
}

</style>
