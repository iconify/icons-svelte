<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggiwcjb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ggiwcjb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:filter-filled" {...props}></Icon>
