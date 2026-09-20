<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhndg-blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chair-sharp" {...props}></Icon>
<style>
:global(.lhndg-blp) {
  fill: currentColor;
  d: path("M4.539 19.346v-1.5H2v-8h3v4.5h14v-4.5h3v8h-2.538v1.5H18.5v-1.5H5.539v1.5zm1.461-6v-4.5H4V5.231h16v3.615h-2v4.5z");
}

</style>
