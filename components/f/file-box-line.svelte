<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqw4okece.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqw4okece"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-box-line" {...props}></Icon>
