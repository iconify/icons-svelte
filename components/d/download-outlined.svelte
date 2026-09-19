<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on3n-9bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="on3n-9bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:download-outlined" {...props}></Icon>
