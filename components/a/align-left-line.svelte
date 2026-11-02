<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjogw_dsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjogw_dsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-left-line" {...props}></Icon>
