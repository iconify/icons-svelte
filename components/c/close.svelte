<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g42bubbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g42bubbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:close" {...props}></Icon>
