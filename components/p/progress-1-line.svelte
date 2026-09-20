<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3rbbxb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3rbbxb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-1-line" {...props}></Icon>
