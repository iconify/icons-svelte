<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agv0_db3u.css';
import '../../css/s/s_kdtkgoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="agv0_db3u"/><path class="s_kdtkgoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bh-4x3" {...props}></Icon>
