<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvtq6ac7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtq6ac7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-home-outline" {...props}></Icon>
