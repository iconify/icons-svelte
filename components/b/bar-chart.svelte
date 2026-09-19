<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m184yjbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m184yjbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bar-chart" {...props}></Icon>
