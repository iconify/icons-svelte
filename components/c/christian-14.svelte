<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nww_-sbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nww_-sbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:christian-14" {...props}></Icon>
