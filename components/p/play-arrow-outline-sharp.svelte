<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgaoxullz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:play-arrow-outline-sharp" {...props}></Icon>
<style>
:global(.pgaoxullz) {
  fill: currentColor;
  d: path("M9 17.192V6.808L17.154 12zm1-1.842L15.289 12L10 8.65z");
}

</style>
