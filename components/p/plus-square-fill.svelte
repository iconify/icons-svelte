<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2mzdq3zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w2mzdq3zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:plus-square-fill" {...props}></Icon>
