<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie46jk5tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie46jk5tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ethernet-port-line" {...props}></Icon>
