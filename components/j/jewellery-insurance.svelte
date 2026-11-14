<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzu4jvhbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:jewellery-insurance" {...props}></Icon>
<style>
:global(.mzu4jvhbq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 15.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0M9.152 4.914l.411-.686a1.5 1.5 0 0 1 1.286-.728h2.302a1.5 1.5 0 0 1 1.286.728l.411.686a1.5 1.5 0 0 1-.31 1.91l-1.562 1.339a1.5 1.5 0 0 1-1.952 0L9.462 6.824a1.5 1.5 0 0 1-.31-1.91");
}

</style>
