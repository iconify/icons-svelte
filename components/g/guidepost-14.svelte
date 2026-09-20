<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3tnrzbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m3tnrzbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:guidepost-14" {...props}></Icon>
