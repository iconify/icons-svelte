<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsp2tpz6a.css';
import '../../css/w/wjbqyhpxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qsp2tpz6a"/><path class="wjbqyhpxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cross-mark" {...props}></Icon>
