<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmvtqzacp.css';
import '../../css/y/yox3j-b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmvtqzacp"/><path class="yox3j-b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-book" {...props}></Icon>
