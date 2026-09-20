<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q18v9vb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-tab-rtl-sharp" {...props}></Icon>
<style>
:global(.q18v9vb-x) {
  fill: currentColor;
  d: path("M4 17.5H3v-11h1zm7.673-.212L6.385 12l5.288-5.288l.688.688l-4.055 4.1H21v1H8.287l4.1 4.1z");
}

</style>
