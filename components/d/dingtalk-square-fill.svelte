<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9bpb6big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n9bpb6big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dingtalk-square-fill" {...props}></Icon>
