<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="idc93-t_d"/><path class="wmavafyqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lamp-floor-fill" {...props}></Icon>
<style>
:global(.idc93-t_d) {
  fill: currentColor;
  d: path("M13.4199 1C14.137 1 14.8 1.384 15.1562 2.007L19.7344 10.007C20.4973 11.34 19.534 13 17.998 13H6.0019C4.4659 13 3.5026 11.34 4.2656 10.007L8.8437 2.007C9.2 1.384 9.8629 1 10.5801 1H13.4199Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wmavafyqn) {
  d: path("M12 12V22M9 22H15");
}

</style>
