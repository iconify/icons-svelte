<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x6vqwutyw"/><path class="jtc3aq6jc"/><path class="sbgi_9rnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fishing-umbrella" {...props}></Icon>
<style>
:global(.jtc3aq6jc) {
  d: path("M12 2.5C9.5 5 8 8 7.75 11M12 2.5C14.5 5 16 8 16.25 11M18 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.sbgi_9rnf) {
  d: path("M19.5 17v2.5a2.25 2.25 0 0 1-4.5 0v-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x6vqwutyw) {
  d: path("M2.5 11a9.5 8.5 0 0 1 19 0Zm9.5 0v10.5");
}

</style>
