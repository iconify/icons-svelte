<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx80fdgqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xx80fdgqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:play-square-filled" {...props}></Icon>
