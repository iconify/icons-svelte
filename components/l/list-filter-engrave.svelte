<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bi-h1cbhh.css';
import '../../css/m/ms02r72gm.css';
import '../../css/m/m9ll0eb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bi-h1cbhh"/><path class="ms02r72gm wm-shadow"/><path class="m9ll0eb5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-filter-engrave" {...props}></Icon>
