<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdyr0c5sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-share-sharp" {...props}></Icon>
<style>
:global(.tdyr0c5sz) {
  fill: currentColor;
  d: path("M8.77 15.5h1v-3h3.61l-1.588 1.58l.708.708L15.288 12L12.5 9.211l-.708.689l1.57 1.6H8.769zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
