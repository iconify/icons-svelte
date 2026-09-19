<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyze-2b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iyze-2b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:codepen-square-filled" {...props}></Icon>
