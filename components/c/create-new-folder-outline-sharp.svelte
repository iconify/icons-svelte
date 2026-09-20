<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1o_r7a_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:create-new-folder-outline-sharp" {...props}></Icon>
<style>
:global(.b1o_r7a_r) {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm1-1h16V8h-8.81L9.195 6H4zm0 0V6zm10.5-2.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
