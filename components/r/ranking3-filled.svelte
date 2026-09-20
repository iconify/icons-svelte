<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywnzoobqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywnzoobqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ranking3-filled" {...props}></Icon>
