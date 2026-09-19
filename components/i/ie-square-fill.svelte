<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2dxxfbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y2dxxfbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ie-square-fill" {...props}></Icon>
