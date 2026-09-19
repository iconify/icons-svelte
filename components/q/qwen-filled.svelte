<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4p5sgccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l4p5sgccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:qwen-filled" {...props}></Icon>
