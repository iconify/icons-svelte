<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-77igb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c-77igb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dribbble-square-filled" {...props}></Icon>
