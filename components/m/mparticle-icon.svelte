<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":214};
const content = `<path class="j371nvhhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:mparticle-icon" {...props}></Icon>
<style>
:global(.j371nvhhn) {
  d: path("M256 106.654v53.308l-85.333 53.32v-53.32zm-85.333 0v53.308l-85.334 53.32v-53.32zm-85.334 0v53.308L0 213.282v-53.32zM256 0v53.32l-85.333 53.321v-53.32zm-85.333 0v53.32l-85.334 53.321v-53.32zM85.333 0v53.32L0 106.642v-53.32z");
}

</style>
