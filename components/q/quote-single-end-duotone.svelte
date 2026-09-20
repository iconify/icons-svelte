<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmtv38vfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmtv38vfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:quote-single-end-duotone" {...props}></Icon>
