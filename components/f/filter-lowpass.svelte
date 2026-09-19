<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr8snkabi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vr8snkabi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-lowpass" {...props}></Icon>
