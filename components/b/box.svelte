<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmp6hbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbmp6hbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:box" {...props}></Icon>
