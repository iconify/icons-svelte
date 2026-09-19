<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y7yekevqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:levelsfyi" {...props}></Icon>
<style>
:global(.y7yekevqy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.46 7.983V42.5H8.504v-6.887h6.527v-6.728h6.848v-6.807h6.767V15.27h7.328V7.982zM29.887 5.5L5.539 30.007");
}

</style>
