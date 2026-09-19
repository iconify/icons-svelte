<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av9ti37jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="av9ti37jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:insert-row-left-outlined" {...props}></Icon>
