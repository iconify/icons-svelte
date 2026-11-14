<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6iz3aciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:issue-pin" {...props}></Icon>
<style>
:global(.d6iz3aciw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5s7-6.5 7-12a7 7 0 0 0-14 0c0 5.5 7 12 7 12M12 6v4.5m0 3h.01");
}

</style>
