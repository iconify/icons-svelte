<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc458yufi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc458yufi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:father-christmas-line" {...props}></Icon>
