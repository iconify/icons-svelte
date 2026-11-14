<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rw52jubvw"/><path class="d5xlclvji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-press" {...props}></Icon>
<style>
:global(.d5xlclvji) {
  d: path("M7.5 14h9v3h-9Z");
}

:global(.rw52jubvw) {
  d: path("M3 20.5h18m-16.5 0V7h15v13.5M12 3v11M8.5 3h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
