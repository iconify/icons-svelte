<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tndf3ybwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tndf3ybwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:lock" {...props}></Icon>
