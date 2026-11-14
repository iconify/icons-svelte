<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpbfo_bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clean-kitchen" {...props}></Icon>
<style>
:global(.gpbfo_bii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5h14V16a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4ZM2.5 13H4m1-4.5h12m-6-2v2m8.192-5.067l.267.413a1.5 1.5 0 0 0 .445.445l.413.267a.526.526 0 0 1 0 .884l-.413.267a1.5 1.5 0 0 0-.445.445l-.267.413a.526.526 0 0 1-.884 0l-.267-.413a1.5 1.5 0 0 0-.445-.445l-.413-.267a.526.526 0 0 1 0-.884l.413-.267a1.5 1.5 0 0 0 .445-.445l.267-.413a.526.526 0 0 1 .884 0");
}

</style>
