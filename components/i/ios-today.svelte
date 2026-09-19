<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcl3y6bkj.css';
import '../../css/p/plthgm9xi.css';
import '../../css/z/zn72xdbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcl3y6bkj"/><path class="plthgm9xi"/><path class="zn72xdbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-today" {...props}></Icon>
