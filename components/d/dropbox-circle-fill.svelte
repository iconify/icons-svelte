<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwc9mxbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vwc9mxbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dropbox-circle-fill" {...props}></Icon>
