<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy1j1mu6r.css';
import '../../css/q/qmrmd-8xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yy1j1mu6r"/><path class="qmrmd-8xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:home" {...props}></Icon>
