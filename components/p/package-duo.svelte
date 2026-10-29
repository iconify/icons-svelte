<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vncwlbbyf.css';
import '../../css/s/sqx3j0bau.css';
import '../../css/r/rojp4pxea.css';
import '../../css/a/a91ndtnyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vncwlbbyf"/><path class="sqx3j0bau wm-a"/><path class="rojp4pxea"/><path class="a91ndtnyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:package-duo" {...props}></Icon>
