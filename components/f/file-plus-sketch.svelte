<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hsqhbfcjf.css';
import '../../css/o/oyv0mybyv.css';
import '../../css/k/knxdme06z.css';
import '../../css/o/o8l__-5ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hsqhbfcjf"/><path class="oyv0mybyv wm-a"/><path class="knxdme06z wm-k"/><path class="o8l__-5ww wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-plus-sketch" {...props}></Icon>
