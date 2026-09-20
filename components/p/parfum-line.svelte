<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw_fchlfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw_fchlfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parfum-line" {...props}></Icon>
