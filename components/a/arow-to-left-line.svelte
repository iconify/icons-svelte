<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1c6xhbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1c6xhbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arow-to-left-line" {...props}></Icon>
