<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqyqcubos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:check-small" {...props}></Icon>
<style>
:global(.pqyqcubos) {
  fill: currentColor;
  d: path("M10 15.689L6.712 12.4l.688-.688l2.6 2.6l6.6-6.6l.688.688z");
}

</style>
