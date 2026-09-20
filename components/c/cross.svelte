<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc4e6v2qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="yc4e6v2qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cross" {...props}></Icon>
