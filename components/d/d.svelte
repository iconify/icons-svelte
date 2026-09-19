<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqgm7gb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":562,"height":768};
const content = `<path class="yqgm7gb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:d" {...props}></Icon>
