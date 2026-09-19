<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_8o_25te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g_8o_25te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:column-height-outlined" {...props}></Icon>
