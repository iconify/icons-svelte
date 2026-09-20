<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnn422bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnn422bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:attachment-add" {...props}></Icon>
