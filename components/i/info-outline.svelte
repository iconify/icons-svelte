<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4qgwbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lc4qgwbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:info-outline" {...props}></Icon>
