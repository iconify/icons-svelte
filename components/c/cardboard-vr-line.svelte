<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw-pdwb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw-pdwb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cardboard-vr-line" {...props}></Icon>
