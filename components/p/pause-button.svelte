<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w2vml8clc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:pause-button" {...props}></Icon>
<style>
:global(.w2vml8clc) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M36.57 96h18.29V32H36.57zm36.57-64v64h18.29V32z");
}

</style>
