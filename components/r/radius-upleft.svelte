<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtxx3f7-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mtxx3f7-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:radius-upleft" {...props}></Icon>
