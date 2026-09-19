<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ns52iae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y0ns52iae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:crown" {...props}></Icon>
