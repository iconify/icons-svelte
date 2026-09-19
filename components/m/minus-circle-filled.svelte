<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eerz48b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eerz48b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:minus-circle-filled" {...props}></Icon>
