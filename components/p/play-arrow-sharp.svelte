<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8mthqbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:play-arrow-sharp" {...props}></Icon>
<style>
:global(.p8mthqbzg) {
  fill: currentColor;
  d: path("M9 17.192V6.808L17.154 12z");
}

</style>
