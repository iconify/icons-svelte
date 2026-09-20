<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwbdgq.css';
import '../../css/s/so-from-76.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwbdgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:bluesky" {...props}></Icon>
