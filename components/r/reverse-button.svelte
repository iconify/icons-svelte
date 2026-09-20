<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jd_8jwb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:reverse-button" {...props}></Icon>
<style>
:global(.jd_8jwb_g) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M106 112.5v-97L22 64z");
}

</style>
