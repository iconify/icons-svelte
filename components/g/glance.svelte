<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuysp5byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuysp5byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:glance" {...props}></Icon>
