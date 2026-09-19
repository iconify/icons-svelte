<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtgrmkj5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rtgrmkj5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:reconciliation" {...props}></Icon>
