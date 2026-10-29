<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rojp4pxea.css';
import '../../css/a/a91ndtnyb.css';
import '../../css/s/sqx3j0bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rojp4pxea"/><path class="a91ndtnyb"/><path class="sqx3j0bau wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:package" {...props}></Icon>
