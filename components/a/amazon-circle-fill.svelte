<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykkks98ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ykkks98ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:amazon-circle-fill" {...props}></Icon>
