<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfo6gbb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfo6gbb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:leaderprice" {...props}></Icon>
