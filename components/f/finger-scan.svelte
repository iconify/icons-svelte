<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hkzeubbqo.css';
import '../../css/q/qkx_1d5id.css';
import '../../css/j/j5ec80dni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hkzeubbqo"/><path class="qkx_1d5id"/><path class="j5ec80dni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:finger-scan" {...props}></Icon>
