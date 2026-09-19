<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frhjjwbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="frhjjwbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:line-chart-outlined" {...props}></Icon>
