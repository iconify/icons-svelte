<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc715-kwz.css';
import '../../css/h/hustz32ji.css';
import '../../css/a/aqstzpbjn.css';
import '../../css/h/h48zvybiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yc715-kwz"/><path class="hustz32ji wm-a"/><path class="aqstzpbjn wm-a"/><path class="h48zvybiq wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:clipboard-list" {...props}></Icon>
