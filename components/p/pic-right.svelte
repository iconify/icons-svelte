<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e60q68won.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e60q68won"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pic-right" {...props}></Icon>
