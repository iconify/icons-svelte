<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f70cc6byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f70cc6byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-refresh-outline" {...props}></Icon>
