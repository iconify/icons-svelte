<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odv875mne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-justify-stretch-sharp" {...props}></Icon>
<style>
:global(.odv875mne) {
  fill: currentColor;
  d: path("M20 22V2h2v20zM2 22V2h2v20zm11-12V7h5v3zm-7 0V7h5v3zm7 7v-3h5v3zm-7 0v-3h5v3z");
}

</style>
