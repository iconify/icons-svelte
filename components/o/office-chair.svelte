<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpl9ltrpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpl9ltrpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-chair" {...props}></Icon>
