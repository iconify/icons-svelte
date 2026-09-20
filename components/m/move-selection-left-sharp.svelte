<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1qmydbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:move-selection-left-sharp" {...props}></Icon>
<style>
:global(.t1qmydbom) {
  fill: currentColor;
  d: path("M3 17.039V6.961h10.077v10.077zm12.808-8.847v-1.23h1.23v1.23zm0 8.846v-1.23h1.23v1.23zm3.961-8.846v-1.23H21v1.23zm0 4.423v-1.23H21v1.23zm0 4.423v-1.23H21v1.23z");
}

</style>
