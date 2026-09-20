<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jixoakntt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-large-outline-sharp" {...props}></Icon>
<style>
:global(.jixoakntt) {
  fill: currentColor;
  d: path("M5.923 15.616V5.923h11.693v9.693zM3 19v-1h17V5h1v14z");
}

</style>
