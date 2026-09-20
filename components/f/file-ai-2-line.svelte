<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi8s1omqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi8s1omqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-ai-2-line" {...props}></Icon>
