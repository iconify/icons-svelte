<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yni2ox9wx.css';
import '../../css/r/rr69ofbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yni2ox9wx"/><path class="primary rr69ofbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fast-forward-duo" {...props}></Icon>
