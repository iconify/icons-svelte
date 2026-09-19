<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv_brepse.css';
import '../../css/v/vn3jj0b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="vn3jj0b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:clock-circle" {...props}></Icon>
