<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmoj1jb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:cleaning-services-outline-sharp" {...props}></Icon>
<style>
:global(.fmoj1jb3l) {
  fill: currentColor;
  d: path("M4 22V11.712h5.712V2h4.577v9.712H20V22zm1-1h2.75v-4.02h1V21h2.75v-4.02h1V21h2.75v-4.02h1V21H19v-8.288H5zm8.289-9.288V3h-2.577v8.712zm0 0h-2.577z");
}

</style>
