<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmtew4bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":112,"height":384};
const content = `<path class="qmtew4bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-left" {...props}></Icon>
