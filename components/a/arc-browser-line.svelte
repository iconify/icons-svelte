<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3nhiorgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3nhiorgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arc-browser-line" {...props}></Icon>
