<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clyynnbbx.css';
import '../../css/z/z-nk8wbnr.css';
import '../../css/x/xy4cuobbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="clyynnbbx"/><path class="z-nk8wbnr"/><path class="xy4cuobbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mail-twotone" {...props}></Icon>
