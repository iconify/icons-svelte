<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw41954fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pw41954fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dingtalk" {...props}></Icon>
