<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rujup72zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rujup72zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-warning-fill" {...props}></Icon>
