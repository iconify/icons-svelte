<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y75p7nnij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y75p7nnij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fall-outlined" {...props}></Icon>
