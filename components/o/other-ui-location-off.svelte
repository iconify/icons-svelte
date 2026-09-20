<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwildgbog.css';
import '../../css/m/mfymmub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bwildgbog"/><path class="mfymmub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-location-off" {...props}></Icon>
