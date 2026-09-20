<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2xtlpgil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:edit-location-sharp" {...props}></Icon>
<style>
:global(.t2xtlpgil) {
  fill: currentColor;
  d: path("M8.5 13.5h1.45l3.9-3.925l-1.425-1.425l-3.925 3.9zm6.075-4.65l.975-.975l-1.425-1.425l-.975.975zM12 22q-4.025-3.425-6.012-6.362T4 10.2q0-3.75 2.413-5.975T12 2t5.588 2.225T20 10.2q0 2.5-1.987 5.438T12 22");
}

</style>
