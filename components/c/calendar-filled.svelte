<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1024j9lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1024j9lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:calendar-filled" {...props}></Icon>
