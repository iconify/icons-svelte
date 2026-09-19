<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmqiz0x_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rmqiz0x_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dot-net-outlined" {...props}></Icon>
