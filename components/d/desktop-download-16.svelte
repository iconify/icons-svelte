<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjfl23hqz.css';
import '../../css/i/i2hb8p_7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xjfl23hqz"/><path class="i2hb8p_7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:desktop-download-16" {...props}></Icon>
