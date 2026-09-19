<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th2y76b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="th2y76b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:behance-outline" {...props}></Icon>
