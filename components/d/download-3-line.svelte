<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvs-sobwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvs-sobwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-3-line" {...props}></Icon>
