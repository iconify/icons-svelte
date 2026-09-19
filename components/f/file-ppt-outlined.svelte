<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsc6dmdar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zsc6dmdar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-ppt-outlined" {...props}></Icon>
