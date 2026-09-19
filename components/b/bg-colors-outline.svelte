<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoofr1q7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xoofr1q7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bg-colors-outline" {...props}></Icon>
