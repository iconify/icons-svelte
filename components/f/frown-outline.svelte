<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp0pkwbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vp0pkwbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:frown-outline" {...props}></Icon>
