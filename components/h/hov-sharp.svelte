<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5qk1gqvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:hov-sharp" {...props}></Icon>
<style>
:global(.c5qk1gqvw) {
  fill: currentColor;
  d: path("m12 21l-5-9.02L12 3l5 8.98z");
}

</style>
