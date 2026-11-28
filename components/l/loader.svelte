<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg1eb4bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg1eb4bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:loader" {...props}></Icon>
