<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib167_bsp.css';
import '../../css/y/yv_brepse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ib167_bsp"/><path class="yv_brepse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:plus-circle" {...props}></Icon>
