<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqhcpqbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:menu-sharp" {...props}></Icon>
<style>
:global(.cqhcpqbdr) {
  fill: currentColor;
  d: path("M4 17.27v-1h16v1zm0-4.77v-1h16v1zm0-4.77v-1h16v1z");
}

</style>
