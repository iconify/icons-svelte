<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh_wv8bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_wv8bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:egg-fried-filled" {...props}></Icon>
