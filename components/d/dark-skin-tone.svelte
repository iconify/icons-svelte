<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cf5ovs9yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:dark-skin-tone" {...props}></Icon>
<style>
:global(.cf5ovs9yz) {
  fill: var(--svg-color--584539, #584539);
  d: path("M10 10h108v108H10z");
}

</style>
