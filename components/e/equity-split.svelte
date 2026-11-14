<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5w4bbbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:equity-split" {...props}></Icon>
<style>
:global(.i5w4bbbna) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 10.75v-8q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q13.176 2 13.25 2q3.624 0 6.187 2.563T22 10.75q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m-1.25 2h7.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.624-2.563 6.187T10.5 22.25t-6.187-2.563T1.75 13.5t2.563-6.187T10.5 4.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
