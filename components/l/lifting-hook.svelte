<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhvnldbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lifting-hook" {...props}></Icon>
<style>
:global(.yhvnldbvv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5V8m0 0v6a4 4 0 1 1-4 0");
}

</style>
