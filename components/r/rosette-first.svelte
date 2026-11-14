<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h84qk6b1q"/><path class="p6ujunb9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rosette-first" {...props}></Icon>
<style>
:global(.h84qk6b1q) {
  d: path("m18.164 7.926l-.599-.771a1.75 1.75 0 0 1-.361-.916l-.079-.864a1.66 1.66 0 0 0-1.5-1.5l-.864-.079a1.75 1.75 0 0 1-.916-.361l-.771-.599a1.75 1.75 0 0 0-2.148 0l-.771.599a1.75 1.75 0 0 1-.916.361l-.864.079a1.66 1.66 0 0 0-1.5 1.5l-.079.864a1.75 1.75 0 0 1-.361.916l-.599.771a1.75 1.75 0 0 0 0 2.148l.599.771a1.75 1.75 0 0 1 .361.916l.079.864a1.66 1.66 0 0 0 1.5 1.5l.864.079a1.75 1.75 0 0 1 .916.361l.771.599a1.75 1.75 0 0 0 2.148 0l.771-.599a1.75 1.75 0 0 1 .916-.361l.864-.079a1.66 1.66 0 0 0 1.5-1.5l.079-.864a1.75 1.75 0 0 1 .361-.916l.599-.771a1.75 1.75 0 0 0 0-2.148");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p6ujunb9t) {
  d: path("M9.25 14.25L7 21l1.75-1l1.75 1.5L12 16l1.5 5.5l1.75-1.5L17 21l-2.25-6.75M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
