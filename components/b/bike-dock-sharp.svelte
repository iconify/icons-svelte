<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzj1fbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bike-dock-sharp" {...props}></Icon>
<style>
:global(.tuzj1fbuv) {
  fill: currentColor;
  d: path("M4 20v-1l4.77-.917L9.807 4h4.384l1.039 14.083L20 19v1zm6.808-1.827h2.384V5h-2.384z");
}

</style>
