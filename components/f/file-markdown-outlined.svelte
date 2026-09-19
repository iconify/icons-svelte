<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bug6acbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bug6acbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-markdown-outlined" {...props}></Icon>
