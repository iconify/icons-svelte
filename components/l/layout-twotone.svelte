<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8_qb9bev.css';
import '../../css/c/cjf6f3gxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u8_qb9bev"/><path class="cjf6f3gxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:layout-twotone" {...props}></Icon>
