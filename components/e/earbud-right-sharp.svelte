<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1aue5hyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:earbud-right-sharp" {...props}></Icon>
<style>
:global(.z1aue5hyq) {
  fill: currentColor;
  d: path("M12.442 21V5H20v6.673h-2.788V21zm-3.48-7.327q-2.116 0-3.539-1.586T4 8.327t1.423-3.75T8.961 3h.731v10.673z");
}

</style>
