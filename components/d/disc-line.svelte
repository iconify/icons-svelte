<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zru76bzsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zru76bzsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disc-line" {...props}></Icon>
