<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz0nrs-zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz0nrs-zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-symphony-t1" {...props}></Icon>
