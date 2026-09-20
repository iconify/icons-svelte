<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po2610bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-landscape-sharp" {...props}></Icon>
<style>
:global(.po2610bgk) {
  fill: currentColor;
  d: path("M2 18V5.923h4.83V5h3.686v.923H22V18zm4.088-5.49q.22-.222.22-.55t-.222-.548t-.549-.22t-.547.222t-.22.549t.22.548t.55.22t.548-.222");
}

</style>
