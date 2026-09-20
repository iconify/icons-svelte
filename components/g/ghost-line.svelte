<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e85dptbxk.css';
import '../../css/y/yijn-abxr.css';
import '../../css/m/milycbc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e85dptbxk"/><path class="yijn-abxr"/><path class="milycbc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ghost-line" {...props}></Icon>
