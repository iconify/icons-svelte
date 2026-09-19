<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvhcdebcd.css';
import '../../css/g/gsarlxfwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvhcdebcd"/><path class="gsarlxfwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-download" {...props}></Icon>
