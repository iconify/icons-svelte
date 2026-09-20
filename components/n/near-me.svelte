<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea3ri1q9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:near-me" {...props}></Icon>
<style>
:global(.ea3ri1q9g) {
  fill: currentColor;
  d: path("m12.9 21l-2.85-7.05L3 11.1V9.7L21 3l-6.7 18z");
}

</style>
