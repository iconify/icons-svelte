<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgr19of2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgr19of2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rectangle-fill" {...props}></Icon>
