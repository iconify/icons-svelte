<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywa-3-i-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ywa-3-i-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:highlight-fill" {...props}></Icon>
