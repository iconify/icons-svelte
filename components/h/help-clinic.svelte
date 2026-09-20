<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t96m4wjqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:help-clinic" {...props}></Icon>
<style>
:global(.t96m4wjqw) {
  fill: currentColor;
  d: path("M11 17h2v-5h-2zm1.713-7.288Q13 9.425 13 9t-.288-.712T12 8t-.712.288T11 9t.288.713T12 10t.713-.288M4 21V9l8-6l8 6v12z");
}

</style>
