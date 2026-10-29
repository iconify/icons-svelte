<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6dmbibyf.css';
import '../../css/r/r6hiy7bns.css';
import '../../css/y/yi94j5zbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6dmbibyf wm-k"/><path class="r6hiy7bns wm-k"/><path class="wm-a yi94j5zbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:accessibility" {...props}></Icon>
