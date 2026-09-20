<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3cr0pqzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:curtains-closed-sharp" {...props}></Icon>
<style>
:global(.i3cr0pqzy) {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm9-2h2V5h-2z");
}

</style>
