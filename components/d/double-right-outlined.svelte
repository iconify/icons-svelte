<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd8uw_5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rfd8uw_5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:double-right-outlined" {...props}></Icon>
