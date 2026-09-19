<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh1d9-p_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xh1d9-p_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dropbox-outline" {...props}></Icon>
