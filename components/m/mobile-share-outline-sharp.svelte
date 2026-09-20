<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyun6v4ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-share-outline-sharp" {...props}></Icon>
<style>
:global(.iyun6v4ln) {
  fill: currentColor;
  d: path("M8.77 15.5h1v-3h3.61l-1.588 1.58l.708.708L15.288 12L12.5 9.211l-.708.689l1.57 1.6H8.769zM6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
