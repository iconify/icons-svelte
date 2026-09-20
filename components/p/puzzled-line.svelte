<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqebvetyd.css';
import '../../css/r/rurheh2hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqebvetyd"/><path class="rurheh2hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:puzzled-line" {...props}></Icon>
