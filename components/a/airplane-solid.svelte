<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rablo__dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rablo__dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:airplane-solid" {...props}></Icon>
