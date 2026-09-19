<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt25qkitr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xt25qkitr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ant-design" {...props}></Icon>
