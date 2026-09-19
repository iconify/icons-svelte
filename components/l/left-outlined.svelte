<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-t05dcer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y-t05dcer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:left-outlined" {...props}></Icon>
