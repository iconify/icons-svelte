<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddddgibgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddddgibgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-portrait-filled" {...props}></Icon>
