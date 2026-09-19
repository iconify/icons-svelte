<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy66ctbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wy66ctbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:code-filled" {...props}></Icon>
