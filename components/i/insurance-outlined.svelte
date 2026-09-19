<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihyzp7bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ihyzp7bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:insurance-outlined" {...props}></Icon>
