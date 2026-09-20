<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yovgyab1e.css';
import '../../css/x/x218cyb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yovgyab1e"/><path class="x218cyb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:desktop-download-24" {...props}></Icon>
