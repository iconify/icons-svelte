<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="piyq7jbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fairemail" {...props}></Icon>
<style>
:global(.piyq7jbep) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.51 7.18c.84-.55.07-.55 3.49-.55s2.37-.13 3.49.55l12.83 10.07H7.68ZM7.68 17.25v2.5l12.39 9.71l2 1.3c2 1.13 2 1.13 3.93 0l2-1.3l12.39-9.71v-2.5l3.18 2.5v21.63H4.5V19.75Z");
}

</style>
