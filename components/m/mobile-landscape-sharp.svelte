<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdp26t1fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-landscape-sharp" {...props}></Icon>
<style>
:global(.gdp26t1fb) {
  fill: currentColor;
  d: path("M1 19V5h5.1V4h4.8v1H23v14zm4.713-6.288Q6 12.425 6 12t-.288-.712T5 11t-.712.288T4 12t.288.713T5 13t.713-.288");
}

</style>
