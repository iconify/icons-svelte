<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fwt4_36rp.css';
import '../../css/f/fqa1e_awf.css';
import '../../css/y/ykall_bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fwt4_36rp"/><path class="fqa1e_awf"/><path class="ykall_bto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:archive" {...props}></Icon>
