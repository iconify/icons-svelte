<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yln92w6ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yln92w6ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:anthropic-filled" {...props}></Icon>
