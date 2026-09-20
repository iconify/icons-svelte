<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oxq7w1buj"/><path class="tvwpl1bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:npm-icon" {...props}></Icon>
<style>
:global(.oxq7w1buj) {
  fill: var(--svg-color--c12127, #c12127);
  d: path("M0 256V0h256v256z");
}

:global(.tvwpl1bgp) {
  fill: var(--svg-color--fff, #fff);
  d: path("M48 48h160v160h-32V80h-48v128H48z");
}

</style>
