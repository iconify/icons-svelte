<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wld98je9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wld98je9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-warning-fill" {...props}></Icon>
