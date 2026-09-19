<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kb4cgpl.css';
import '../../css/o/on3qdybdj.css';
import '../../css/t/tkqektbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="on3qdybdj"/><path class="tkqektbdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-video-bold" {...props}></Icon>
