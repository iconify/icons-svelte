<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ok2sbil.css';
import '../../css/d/dosvuyafw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ok2sbil"/><path class="dosvuyafw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-png" {...props}></Icon>
