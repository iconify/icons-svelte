<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjbhn1xhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjbhn1xhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bulb" {...props}></Icon>
