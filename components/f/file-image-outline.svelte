<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up-kybbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="up-kybbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-image-outline" {...props}></Icon>
