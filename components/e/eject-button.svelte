<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r9f-debkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:eject-button" {...props}></Icon>
<style>
:global(.r9f-debkk) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M28.08 89.99h72v18h-72zm-.16-12.11h72L63.92 20z");
}

</style>
