<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i623bfbsp.css';
import '../../css/v/veyji9_1k.css';
import '../../css/d/dm587nnti.css';
import '../../css/y/ymmq4nbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i623bfbsp"/><path class="veyji9_1k"/><path class="dm587nnti"/><path class="ymmq4nbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:arduino" {...props}></Icon>
