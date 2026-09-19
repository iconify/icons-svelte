<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cklww9brb.css';
import '../../css/i/i0mrvmytj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cklww9brb"/><path class="i0mrvmytj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:canlendar-twotone" {...props}></Icon>
