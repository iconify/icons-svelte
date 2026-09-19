<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi3d-wbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi3d-wbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dashboard-outline" {...props}></Icon>
