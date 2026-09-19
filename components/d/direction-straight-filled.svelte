<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5u55absk.css';
import '../../css/q/qvuh0pbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s5u55absk"/><path class="qvuh0pbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-straight-filled" {...props}></Icon>
