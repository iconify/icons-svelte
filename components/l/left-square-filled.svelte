<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd9kdwhel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hd9kdwhel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:left-square-filled" {...props}></Icon>
